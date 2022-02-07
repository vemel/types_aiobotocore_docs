<a id="paginators-for-aiobotocore-ssm-module"></a>

# Paginators for aiobotocore SSM module

> [Index](..) > [SSM](.) > Paginators

Auto-generated documentation for
[SSM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
type annotations stubs module
[types-aiobotocore-ssm](https://pypi.org/project/types-aiobotocore-ssm/).

- [Paginators for aiobotocore SSM module](#paginators-for-aiobotocore-ssm-module)
  - [DescribeActivationsPaginator](#describeactivationspaginator)
  - [DescribeAssociationExecutionTargetsPaginator](#describeassociationexecutiontargetspaginator)
  - [DescribeAssociationExecutionsPaginator](#describeassociationexecutionspaginator)
  - [DescribeAutomationExecutionsPaginator](#describeautomationexecutionspaginator)
  - [DescribeAutomationStepExecutionsPaginator](#describeautomationstepexecutionspaginator)
  - [DescribeAvailablePatchesPaginator](#describeavailablepatchespaginator)
  - [DescribeEffectiveInstanceAssociationsPaginator](#describeeffectiveinstanceassociationspaginator)
  - [DescribeEffectivePatchesForPatchBaselinePaginator](#describeeffectivepatchesforpatchbaselinepaginator)
  - [DescribeInstanceAssociationsStatusPaginator](#describeinstanceassociationsstatuspaginator)
  - [DescribeInstanceInformationPaginator](#describeinstanceinformationpaginator)
  - [DescribeInstancePatchStatesPaginator](#describeinstancepatchstatespaginator)
  - [DescribeInstancePatchStatesForPatchGroupPaginator](#describeinstancepatchstatesforpatchgrouppaginator)
  - [DescribeInstancePatchesPaginator](#describeinstancepatchespaginator)
  - [DescribeInventoryDeletionsPaginator](#describeinventorydeletionspaginator)
  - [DescribeMaintenanceWindowExecutionTaskInvocationsPaginator](#describemaintenancewindowexecutiontaskinvocationspaginator)
  - [DescribeMaintenanceWindowExecutionTasksPaginator](#describemaintenancewindowexecutiontaskspaginator)
  - [DescribeMaintenanceWindowExecutionsPaginator](#describemaintenancewindowexecutionspaginator)
  - [DescribeMaintenanceWindowSchedulePaginator](#describemaintenancewindowschedulepaginator)
  - [DescribeMaintenanceWindowTargetsPaginator](#describemaintenancewindowtargetspaginator)
  - [DescribeMaintenanceWindowTasksPaginator](#describemaintenancewindowtaskspaginator)
  - [DescribeMaintenanceWindowsPaginator](#describemaintenancewindowspaginator)
  - [DescribeMaintenanceWindowsForTargetPaginator](#describemaintenancewindowsfortargetpaginator)
  - [DescribeOpsItemsPaginator](#describeopsitemspaginator)
  - [DescribeParametersPaginator](#describeparameterspaginator)
  - [DescribePatchBaselinesPaginator](#describepatchbaselinespaginator)
  - [DescribePatchGroupsPaginator](#describepatchgroupspaginator)
  - [DescribePatchPropertiesPaginator](#describepatchpropertiespaginator)
  - [DescribeSessionsPaginator](#describesessionspaginator)
  - [GetInventoryPaginator](#getinventorypaginator)
  - [GetInventorySchemaPaginator](#getinventoryschemapaginator)
  - [GetOpsSummaryPaginator](#getopssummarypaginator)
  - [GetParameterHistoryPaginator](#getparameterhistorypaginator)
  - [GetParametersByPathPaginator](#getparametersbypathpaginator)
  - [ListAssociationVersionsPaginator](#listassociationversionspaginator)
  - [ListAssociationsPaginator](#listassociationspaginator)
  - [ListCommandInvocationsPaginator](#listcommandinvocationspaginator)
  - [ListCommandsPaginator](#listcommandspaginator)
  - [ListComplianceItemsPaginator](#listcomplianceitemspaginator)
  - [ListComplianceSummariesPaginator](#listcompliancesummariespaginator)
  - [ListDocumentVersionsPaginator](#listdocumentversionspaginator)
  - [ListDocumentsPaginator](#listdocumentspaginator)
  - [ListOpsItemEventsPaginator](#listopsitemeventspaginator)
  - [ListOpsItemRelatedItemsPaginator](#listopsitemrelateditemspaginator)
  - [ListOpsMetadataPaginator](#listopsmetadatapaginator)
  - [ListResourceComplianceSummariesPaginator](#listresourcecompliancesummariespaginator)
  - [ListResourceDataSyncPaginator](#listresourcedatasyncpaginator)

<a id="describeactivationspaginator"></a>

## DescribeActivationsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_activations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeActivationsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeActivationsPaginator = client.get_paginator("describe_activations")
```

Boto3 documentation:
[SSM.Paginator.DescribeActivations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeActivations)

Arguments for `DescribeActivationsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[DescribeActivationsFilterTypeDef](./type_defs.md#describeactivationsfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeActivationsPaginator.paginate` returns
`_PageIterator`\[[DescribeActivationsResultTypeDef](./type_defs.md#describeactivationsresulttypedef)\].

<a id="describeassociationexecutiontargetspaginator"></a>

## DescribeAssociationExecutionTargetsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_association_execution_targets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeAssociationExecutionTargetsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeAssociationExecutionTargetsPaginator = client.get_paginator("describe_association_execution_targets")
```

Boto3 documentation:
[SSM.Paginator.DescribeAssociationExecutionTargets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutionTargets)

Arguments for `DescribeAssociationExecutionTargetsPaginator.paginate` method:

- `AssociationId`: `str` *(required)*
- `ExecutionId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[AssociationExecutionTargetsFilterTypeDef](./type_defs.md#associationexecutiontargetsfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAssociationExecutionTargetsPaginator.paginate` returns
`_PageIterator`\[[DescribeAssociationExecutionTargetsResultTypeDef](./type_defs.md#describeassociationexecutiontargetsresulttypedef)\].

<a id="describeassociationexecutionspaginator"></a>

## DescribeAssociationExecutionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_association_executions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeAssociationExecutionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeAssociationExecutionsPaginator = client.get_paginator("describe_association_executions")
```

Boto3 documentation:
[SSM.Paginator.DescribeAssociationExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutions)

Arguments for `DescribeAssociationExecutionsPaginator.paginate` method:

- `AssociationId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[AssociationExecutionFilterTypeDef](./type_defs.md#associationexecutionfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAssociationExecutionsPaginator.paginate` returns
`_PageIterator`\[[DescribeAssociationExecutionsResultTypeDef](./type_defs.md#describeassociationexecutionsresulttypedef)\].

<a id="describeautomationexecutionspaginator"></a>

## DescribeAutomationExecutionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_automation_executions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeAutomationExecutionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeAutomationExecutionsPaginator = client.get_paginator("describe_automation_executions")
```

Boto3 documentation:
[SSM.Paginator.DescribeAutomationExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationExecutions)

Arguments for `DescribeAutomationExecutionsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[AutomationExecutionFilterTypeDef](./type_defs.md#automationexecutionfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAutomationExecutionsPaginator.paginate` returns
`_PageIterator`\[[DescribeAutomationExecutionsResultTypeDef](./type_defs.md#describeautomationexecutionsresulttypedef)\].

<a id="describeautomationstepexecutionspaginator"></a>

## DescribeAutomationStepExecutionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_automation_step_executions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeAutomationStepExecutionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeAutomationStepExecutionsPaginator = client.get_paginator("describe_automation_step_executions")
```

Boto3 documentation:
[SSM.Paginator.DescribeAutomationStepExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationStepExecutions)

Arguments for `DescribeAutomationStepExecutionsPaginator.paginate` method:

- `AutomationExecutionId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[StepExecutionFilterTypeDef](./type_defs.md#stepexecutionfiltertypedef)\]
- `ReverseOrder`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAutomationStepExecutionsPaginator.paginate` returns
`_PageIterator`\[[DescribeAutomationStepExecutionsResultTypeDef](./type_defs.md#describeautomationstepexecutionsresulttypedef)\].

<a id="describeavailablepatchespaginator"></a>

## DescribeAvailablePatchesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_available_patches")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeAvailablePatchesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeAvailablePatchesPaginator = client.get_paginator("describe_available_patches")
```

Boto3 documentation:
[SSM.Paginator.DescribeAvailablePatches](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAvailablePatches)

Arguments for `DescribeAvailablePatchesPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeAvailablePatchesPaginator.paginate` returns
`_PageIterator`\[[DescribeAvailablePatchesResultTypeDef](./type_defs.md#describeavailablepatchesresulttypedef)\].

<a id="describeeffectiveinstanceassociationspaginator"></a>

## DescribeEffectiveInstanceAssociationsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_effective_instance_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeEffectiveInstanceAssociationsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeEffectiveInstanceAssociationsPaginator = client.get_paginator("describe_effective_instance_associations")
```

Boto3 documentation:
[SSM.Paginator.DescribeEffectiveInstanceAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectiveInstanceAssociations)

Arguments for `DescribeEffectiveInstanceAssociationsPaginator.paginate` method:

- `InstanceId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEffectiveInstanceAssociationsPaginator.paginate` returns
`_PageIterator`\[[DescribeEffectiveInstanceAssociationsResultTypeDef](./type_defs.md#describeeffectiveinstanceassociationsresulttypedef)\].

<a id="describeeffectivepatchesforpatchbaselinepaginator"></a>

## DescribeEffectivePatchesForPatchBaselinePaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_effective_patches_for_patch_baseline")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeEffectivePatchesForPatchBaselinePaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeEffectivePatchesForPatchBaselinePaginator = client.get_paginator("describe_effective_patches_for_patch_baseline")
```

Boto3 documentation:
[SSM.Paginator.DescribeEffectivePatchesForPatchBaseline](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectivePatchesForPatchBaseline)

Arguments for `DescribeEffectivePatchesForPatchBaselinePaginator.paginate`
method:

- `BaselineId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeEffectivePatchesForPatchBaselinePaginator.paginate` returns
`_PageIterator`\[[DescribeEffectivePatchesForPatchBaselineResultTypeDef](./type_defs.md#describeeffectivepatchesforpatchbaselineresulttypedef)\].

<a id="describeinstanceassociationsstatuspaginator"></a>

## DescribeInstanceAssociationsStatusPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_instance_associations_status")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInstanceAssociationsStatusPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInstanceAssociationsStatusPaginator = client.get_paginator("describe_instance_associations_status")
```

Boto3 documentation:
[SSM.Paginator.DescribeInstanceAssociationsStatus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceAssociationsStatus)

Arguments for `DescribeInstanceAssociationsStatusPaginator.paginate` method:

- `InstanceId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceAssociationsStatusPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceAssociationsStatusResultTypeDef](./type_defs.md#describeinstanceassociationsstatusresulttypedef)\].

<a id="describeinstanceinformationpaginator"></a>

## DescribeInstanceInformationPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_instance_information")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInstanceInformationPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInstanceInformationPaginator = client.get_paginator("describe_instance_information")
```

Boto3 documentation:
[SSM.Paginator.DescribeInstanceInformation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceInformation)

Arguments for `DescribeInstanceInformationPaginator.paginate` method:

- `InstanceInformationFilterList`:
  `Sequence`\[[InstanceInformationFilterTypeDef](./type_defs.md#instanceinformationfiltertypedef)\]
- `Filters`:
  `Sequence`\[[InstanceInformationStringFilterTypeDef](./type_defs.md#instanceinformationstringfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstanceInformationPaginator.paginate` returns
`_PageIterator`\[[DescribeInstanceInformationResultTypeDef](./type_defs.md#describeinstanceinformationresulttypedef)\].

<a id="describeinstancepatchstatespaginator"></a>

## DescribeInstancePatchStatesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_instance_patch_states")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInstancePatchStatesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInstancePatchStatesPaginator = client.get_paginator("describe_instance_patch_states")
```

Boto3 documentation:
[SSM.Paginator.DescribeInstancePatchStates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStates)

Arguments for `DescribeInstancePatchStatesPaginator.paginate` method:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstancePatchStatesPaginator.paginate` returns
`_PageIterator`\[[DescribeInstancePatchStatesResultTypeDef](./type_defs.md#describeinstancepatchstatesresulttypedef)\].

<a id="describeinstancepatchstatesforpatchgrouppaginator"></a>

## DescribeInstancePatchStatesForPatchGroupPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_instance_patch_states_for_patch_group")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInstancePatchStatesForPatchGroupPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInstancePatchStatesForPatchGroupPaginator = client.get_paginator("describe_instance_patch_states_for_patch_group")
```

Boto3 documentation:
[SSM.Paginator.DescribeInstancePatchStatesForPatchGroup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStatesForPatchGroup)

Arguments for `DescribeInstancePatchStatesForPatchGroupPaginator.paginate`
method:

- `PatchGroup`: `str` *(required)*
- `Filters`:
  `Sequence`\[[InstancePatchStateFilterTypeDef](./type_defs.md#instancepatchstatefiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstancePatchStatesForPatchGroupPaginator.paginate` returns
`_PageIterator`\[[DescribeInstancePatchStatesForPatchGroupResultTypeDef](./type_defs.md#describeinstancepatchstatesforpatchgroupresulttypedef)\].

<a id="describeinstancepatchespaginator"></a>

## DescribeInstancePatchesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_instance_patches")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInstancePatchesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInstancePatchesPaginator = client.get_paginator("describe_instance_patches")
```

Boto3 documentation:
[SSM.Paginator.DescribeInstancePatches](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatches)

Arguments for `DescribeInstancePatchesPaginator.paginate` method:

- `InstanceId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInstancePatchesPaginator.paginate` returns
`_PageIterator`\[[DescribeInstancePatchesResultTypeDef](./type_defs.md#describeinstancepatchesresulttypedef)\].

<a id="describeinventorydeletionspaginator"></a>

## DescribeInventoryDeletionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_inventory_deletions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeInventoryDeletionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeInventoryDeletionsPaginator = client.get_paginator("describe_inventory_deletions")
```

Boto3 documentation:
[SSM.Paginator.DescribeInventoryDeletions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInventoryDeletions)

Arguments for `DescribeInventoryDeletionsPaginator.paginate` method:

- `DeletionId`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeInventoryDeletionsPaginator.paginate` returns
`_PageIterator`\[[DescribeInventoryDeletionsResultTypeDef](./type_defs.md#describeinventorydeletionsresulttypedef)\].

<a id="describemaintenancewindowexecutiontaskinvocationspaginator"></a>

## DescribeMaintenanceWindowExecutionTaskInvocationsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_execution_task_invocations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowExecutionTaskInvocationsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowExecutionTaskInvocationsPaginator = client.get_paginator("describe_maintenance_window_execution_task_invocations")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowExecutionTaskInvocations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTaskInvocations)

Arguments for
`DescribeMaintenanceWindowExecutionTaskInvocationsPaginator.paginate` method:

- `WindowExecutionId`: `str` *(required)*
- `TaskId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowExecutionTaskInvocationsPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef](./type_defs.md#describemaintenancewindowexecutiontaskinvocationsresulttypedef)\].

<a id="describemaintenancewindowexecutiontaskspaginator"></a>

## DescribeMaintenanceWindowExecutionTasksPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_execution_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowExecutionTasksPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowExecutionTasksPaginator = client.get_paginator("describe_maintenance_window_execution_tasks")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowExecutionTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTasks)

Arguments for `DescribeMaintenanceWindowExecutionTasksPaginator.paginate`
method:

- `WindowExecutionId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowExecutionTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowExecutionTasksResultTypeDef](./type_defs.md#describemaintenancewindowexecutiontasksresulttypedef)\].

<a id="describemaintenancewindowexecutionspaginator"></a>

## DescribeMaintenanceWindowExecutionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_executions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowExecutionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowExecutionsPaginator = client.get_paginator("describe_maintenance_window_executions")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowExecutions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutions)

Arguments for `DescribeMaintenanceWindowExecutionsPaginator.paginate` method:

- `WindowId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowExecutionsPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowExecutionsResultTypeDef](./type_defs.md#describemaintenancewindowexecutionsresulttypedef)\].

<a id="describemaintenancewindowschedulepaginator"></a>

## DescribeMaintenanceWindowSchedulePaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_schedule")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowSchedulePaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowSchedulePaginator = client.get_paginator("describe_maintenance_window_schedule")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowSchedule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowSchedule)

Arguments for `DescribeMaintenanceWindowSchedulePaginator.paginate` method:

- `WindowId`: `str`
- `Targets`: `Sequence`\[[TargetTypeDef](./type_defs.md#targettypedef)\]
- `ResourceType`:
  [MaintenanceWindowResourceTypeType](./literals.md#maintenancewindowresourcetypetype)
- `Filters`:
  `Sequence`\[[PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowSchedulePaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowScheduleResultTypeDef](./type_defs.md#describemaintenancewindowscheduleresulttypedef)\].

<a id="describemaintenancewindowtargetspaginator"></a>

## DescribeMaintenanceWindowTargetsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_targets")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowTargetsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowTargetsPaginator = client.get_paginator("describe_maintenance_window_targets")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowTargets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTargets)

Arguments for `DescribeMaintenanceWindowTargetsPaginator.paginate` method:

- `WindowId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowTargetsPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowTargetsResultTypeDef](./type_defs.md#describemaintenancewindowtargetsresulttypedef)\].

<a id="describemaintenancewindowtaskspaginator"></a>

## DescribeMaintenanceWindowTasksPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_window_tasks")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowTasksPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowTasksPaginator = client.get_paginator("describe_maintenance_window_tasks")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowTasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTasks)

Arguments for `DescribeMaintenanceWindowTasksPaginator.paginate` method:

- `WindowId`: `str` *(required)*
- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowTasksPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowTasksResultTypeDef](./type_defs.md#describemaintenancewindowtasksresulttypedef)\].

<a id="describemaintenancewindowspaginator"></a>

## DescribeMaintenanceWindowsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_windows")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowsPaginator = client.get_paginator("describe_maintenance_windows")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindows)

Arguments for `DescribeMaintenanceWindowsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[MaintenanceWindowFilterTypeDef](./type_defs.md#maintenancewindowfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowsPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowsResultTypeDef](./type_defs.md#describemaintenancewindowsresulttypedef)\].

<a id="describemaintenancewindowsfortargetpaginator"></a>

## DescribeMaintenanceWindowsForTargetPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_maintenance_windows_for_target")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeMaintenanceWindowsForTargetPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeMaintenanceWindowsForTargetPaginator = client.get_paginator("describe_maintenance_windows_for_target")
```

Boto3 documentation:
[SSM.Paginator.DescribeMaintenanceWindowsForTarget](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowsForTarget)

Arguments for `DescribeMaintenanceWindowsForTargetPaginator.paginate` method:

- `Targets`: `Sequence`\[[TargetTypeDef](./type_defs.md#targettypedef)\]
  *(required)*
- `ResourceType`:
  [MaintenanceWindowResourceTypeType](./literals.md#maintenancewindowresourcetypetype)
  *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeMaintenanceWindowsForTargetPaginator.paginate` returns
`_PageIterator`\[[DescribeMaintenanceWindowsForTargetResultTypeDef](./type_defs.md#describemaintenancewindowsfortargetresulttypedef)\].

<a id="describeopsitemspaginator"></a>

## DescribeOpsItemsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_ops_items")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeOpsItemsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeOpsItemsPaginator = client.get_paginator("describe_ops_items")
```

Boto3 documentation:
[SSM.Paginator.DescribeOpsItems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeOpsItems)

Arguments for `DescribeOpsItemsPaginator.paginate` method:

- `OpsItemFilters`:
  `Sequence`\[[OpsItemFilterTypeDef](./type_defs.md#opsitemfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeOpsItemsPaginator.paginate` returns
`_PageIterator`\[[DescribeOpsItemsResponseTypeDef](./type_defs.md#describeopsitemsresponsetypedef)\].

<a id="describeparameterspaginator"></a>

## DescribeParametersPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_parameters")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeParametersPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeParametersPaginator = client.get_paginator("describe_parameters")
```

Boto3 documentation:
[SSM.Paginator.DescribeParameters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeParameters)

Arguments for `DescribeParametersPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[ParametersFilterTypeDef](./type_defs.md#parametersfiltertypedef)\]
- `ParameterFilters`:
  `Sequence`\[[ParameterStringFilterTypeDef](./type_defs.md#parameterstringfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeParametersPaginator.paginate` returns
`_PageIterator`\[[DescribeParametersResultTypeDef](./type_defs.md#describeparametersresulttypedef)\].

<a id="describepatchbaselinespaginator"></a>

## DescribePatchBaselinesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_patch_baselines")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribePatchBaselinesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribePatchBaselinesPaginator = client.get_paginator("describe_patch_baselines")
```

Boto3 documentation:
[SSM.Paginator.DescribePatchBaselines](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchBaselines)

Arguments for `DescribePatchBaselinesPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePatchBaselinesPaginator.paginate` returns
`_PageIterator`\[[DescribePatchBaselinesResultTypeDef](./type_defs.md#describepatchbaselinesresulttypedef)\].

<a id="describepatchgroupspaginator"></a>

## DescribePatchGroupsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_patch_groups")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribePatchGroupsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribePatchGroupsPaginator = client.get_paginator("describe_patch_groups")
```

Boto3 documentation:
[SSM.Paginator.DescribePatchGroups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchGroups)

Arguments for `DescribePatchGroupsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[PatchOrchestratorFilterTypeDef](./type_defs.md#patchorchestratorfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePatchGroupsPaginator.paginate` returns
`_PageIterator`\[[DescribePatchGroupsResultTypeDef](./type_defs.md#describepatchgroupsresulttypedef)\].

<a id="describepatchpropertiespaginator"></a>

## DescribePatchPropertiesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_patch_properties")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribePatchPropertiesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribePatchPropertiesPaginator = client.get_paginator("describe_patch_properties")
```

Boto3 documentation:
[SSM.Paginator.DescribePatchProperties](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchProperties)

Arguments for `DescribePatchPropertiesPaginator.paginate` method:

- `OperatingSystem`: [OperatingSystemType](./literals.md#operatingsystemtype)
  *(required)*
- `Property`: [PatchPropertyType](./literals.md#patchpropertytype) *(required)*
- `PatchSet`: [PatchSetType](./literals.md#patchsettype)
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribePatchPropertiesPaginator.paginate` returns
`_PageIterator`\[[DescribePatchPropertiesResultTypeDef](./type_defs.md#describepatchpropertiesresulttypedef)\].

<a id="describesessionspaginator"></a>

## DescribeSessionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("describe_sessions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import DescribeSessionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: DescribeSessionsPaginator = client.get_paginator("describe_sessions")
```

Boto3 documentation:
[SSM.Paginator.DescribeSessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeSessions)

Arguments for `DescribeSessionsPaginator.paginate` method:

- `State`: [SessionStateType](./literals.md#sessionstatetype) *(required)*
- `Filters`:
  `Sequence`\[[SessionFilterTypeDef](./type_defs.md#sessionfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`DescribeSessionsPaginator.paginate` returns
`_PageIterator`\[[DescribeSessionsResponseTypeDef](./type_defs.md#describesessionsresponsetypedef)\].

<a id="getinventorypaginator"></a>

## GetInventoryPaginator

Type annotations for
`session.create_client("ssm").get_paginator("get_inventory")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import GetInventoryPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: GetInventoryPaginator = client.get_paginator("get_inventory")
```

Boto3 documentation:
[SSM.Paginator.GetInventory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventory)

Arguments for `GetInventoryPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[InventoryFilterTypeDef](./type_defs.md#inventoryfiltertypedef)\]
- `Aggregators`:
  `Sequence`\[[InventoryAggregatorTypeDef](./type_defs.md#inventoryaggregatortypedef)\]
- `ResultAttributes`:
  `Sequence`\[[ResultAttributeTypeDef](./type_defs.md#resultattributetypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetInventoryPaginator.paginate` returns
`_PageIterator`\[[GetInventoryResultTypeDef](./type_defs.md#getinventoryresulttypedef)\].

<a id="getinventoryschemapaginator"></a>

## GetInventorySchemaPaginator

Type annotations for
`session.create_client("ssm").get_paginator("get_inventory_schema")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import GetInventorySchemaPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: GetInventorySchemaPaginator = client.get_paginator("get_inventory_schema")
```

Boto3 documentation:
[SSM.Paginator.GetInventorySchema](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventorySchema)

Arguments for `GetInventorySchemaPaginator.paginate` method:

- `TypeName`: `str`
- `Aggregator`: `bool`
- `SubType`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetInventorySchemaPaginator.paginate` returns
`_PageIterator`\[[GetInventorySchemaResultTypeDef](./type_defs.md#getinventoryschemaresulttypedef)\].

<a id="getopssummarypaginator"></a>

## GetOpsSummaryPaginator

Type annotations for
`session.create_client("ssm").get_paginator("get_ops_summary")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import GetOpsSummaryPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: GetOpsSummaryPaginator = client.get_paginator("get_ops_summary")
```

Boto3 documentation:
[SSM.Paginator.GetOpsSummary](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetOpsSummary)

Arguments for `GetOpsSummaryPaginator.paginate` method:

- `SyncName`: `str`
- `Filters`: `Sequence`\[[OpsFilterTypeDef](./type_defs.md#opsfiltertypedef)\]
- `Aggregators`:
  `Sequence`\[[OpsAggregatorTypeDef](./type_defs.md#opsaggregatortypedef)\]
- `ResultAttributes`:
  `Sequence`\[[OpsResultAttributeTypeDef](./type_defs.md#opsresultattributetypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetOpsSummaryPaginator.paginate` returns
`_PageIterator`\[[GetOpsSummaryResultTypeDef](./type_defs.md#getopssummaryresulttypedef)\].

<a id="getparameterhistorypaginator"></a>

## GetParameterHistoryPaginator

Type annotations for
`session.create_client("ssm").get_paginator("get_parameter_history")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import GetParameterHistoryPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: GetParameterHistoryPaginator = client.get_paginator("get_parameter_history")
```

Boto3 documentation:
[SSM.Paginator.GetParameterHistory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParameterHistory)

Arguments for `GetParameterHistoryPaginator.paginate` method:

- `Name`: `str` *(required)*
- `WithDecryption`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetParameterHistoryPaginator.paginate` returns
`_PageIterator`\[[GetParameterHistoryResultTypeDef](./type_defs.md#getparameterhistoryresulttypedef)\].

<a id="getparametersbypathpaginator"></a>

## GetParametersByPathPaginator

Type annotations for
`session.create_client("ssm").get_paginator("get_parameters_by_path")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import GetParametersByPathPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: GetParametersByPathPaginator = client.get_paginator("get_parameters_by_path")
```

Boto3 documentation:
[SSM.Paginator.GetParametersByPath](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParametersByPath)

Arguments for `GetParametersByPathPaginator.paginate` method:

- `Path`: `str` *(required)*
- `Recursive`: `bool`
- `ParameterFilters`:
  `Sequence`\[[ParameterStringFilterTypeDef](./type_defs.md#parameterstringfiltertypedef)\]
- `WithDecryption`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`GetParametersByPathPaginator.paginate` returns
`_PageIterator`\[[GetParametersByPathResultTypeDef](./type_defs.md#getparametersbypathresulttypedef)\].

<a id="listassociationversionspaginator"></a>

## ListAssociationVersionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_association_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListAssociationVersionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListAssociationVersionsPaginator = client.get_paginator("list_association_versions")
```

Boto3 documentation:
[SSM.Paginator.ListAssociationVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociationVersions)

Arguments for `ListAssociationVersionsPaginator.paginate` method:

- `AssociationId`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAssociationVersionsPaginator.paginate` returns
`_PageIterator`\[[ListAssociationVersionsResultTypeDef](./type_defs.md#listassociationversionsresulttypedef)\].

<a id="listassociationspaginator"></a>

## ListAssociationsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_associations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListAssociationsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListAssociationsPaginator = client.get_paginator("list_associations")
```

Boto3 documentation:
[SSM.Paginator.ListAssociations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociations)

Arguments for `ListAssociationsPaginator.paginate` method:

- `AssociationFilterList`:
  `Sequence`\[[AssociationFilterTypeDef](./type_defs.md#associationfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListAssociationsPaginator.paginate` returns
`_PageIterator`\[[ListAssociationsResultTypeDef](./type_defs.md#listassociationsresulttypedef)\].

<a id="listcommandinvocationspaginator"></a>

## ListCommandInvocationsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_command_invocations")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListCommandInvocationsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListCommandInvocationsPaginator = client.get_paginator("list_command_invocations")
```

Boto3 documentation:
[SSM.Paginator.ListCommandInvocations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommandInvocations)

Arguments for `ListCommandInvocationsPaginator.paginate` method:

- `CommandId`: `str`
- `InstanceId`: `str`
- `Filters`:
  `Sequence`\[[CommandFilterTypeDef](./type_defs.md#commandfiltertypedef)\]
- `Details`: `bool`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCommandInvocationsPaginator.paginate` returns
`_PageIterator`\[[ListCommandInvocationsResultTypeDef](./type_defs.md#listcommandinvocationsresulttypedef)\].

<a id="listcommandspaginator"></a>

## ListCommandsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_commands")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListCommandsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListCommandsPaginator = client.get_paginator("list_commands")
```

Boto3 documentation:
[SSM.Paginator.ListCommands](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommands)

Arguments for `ListCommandsPaginator.paginate` method:

- `CommandId`: `str`
- `InstanceId`: `str`
- `Filters`:
  `Sequence`\[[CommandFilterTypeDef](./type_defs.md#commandfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListCommandsPaginator.paginate` returns
`_PageIterator`\[[ListCommandsResultTypeDef](./type_defs.md#listcommandsresulttypedef)\].

<a id="listcomplianceitemspaginator"></a>

## ListComplianceItemsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_compliance_items")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListComplianceItemsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListComplianceItemsPaginator = client.get_paginator("list_compliance_items")
```

Boto3 documentation:
[SSM.Paginator.ListComplianceItems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceItems)

Arguments for `ListComplianceItemsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[ComplianceStringFilterTypeDef](./type_defs.md#compliancestringfiltertypedef)\]
- `ResourceIds`: `Sequence`\[`str`\]
- `ResourceTypes`: `Sequence`\[`str`\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListComplianceItemsPaginator.paginate` returns
`_PageIterator`\[[ListComplianceItemsResultTypeDef](./type_defs.md#listcomplianceitemsresulttypedef)\].

<a id="listcompliancesummariespaginator"></a>

## ListComplianceSummariesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_compliance_summaries")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListComplianceSummariesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListComplianceSummariesPaginator = client.get_paginator("list_compliance_summaries")
```

Boto3 documentation:
[SSM.Paginator.ListComplianceSummaries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceSummaries)

Arguments for `ListComplianceSummariesPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[ComplianceStringFilterTypeDef](./type_defs.md#compliancestringfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListComplianceSummariesPaginator.paginate` returns
`_PageIterator`\[[ListComplianceSummariesResultTypeDef](./type_defs.md#listcompliancesummariesresulttypedef)\].

<a id="listdocumentversionspaginator"></a>

## ListDocumentVersionsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_document_versions")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListDocumentVersionsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListDocumentVersionsPaginator = client.get_paginator("list_document_versions")
```

Boto3 documentation:
[SSM.Paginator.ListDocumentVersions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocumentVersions)

Arguments for `ListDocumentVersionsPaginator.paginate` method:

- `Name`: `str` *(required)*
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDocumentVersionsPaginator.paginate` returns
`_PageIterator`\[[ListDocumentVersionsResultTypeDef](./type_defs.md#listdocumentversionsresulttypedef)\].

<a id="listdocumentspaginator"></a>

## ListDocumentsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_documents")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListDocumentsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListDocumentsPaginator = client.get_paginator("list_documents")
```

Boto3 documentation:
[SSM.Paginator.ListDocuments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocuments)

Arguments for `ListDocumentsPaginator.paginate` method:

- `DocumentFilterList`:
  `Sequence`\[[DocumentFilterTypeDef](./type_defs.md#documentfiltertypedef)\]
- `Filters`:
  `Sequence`\[[DocumentKeyValuesFilterTypeDef](./type_defs.md#documentkeyvaluesfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListDocumentsPaginator.paginate` returns
`_PageIterator`\[[ListDocumentsResultTypeDef](./type_defs.md#listdocumentsresulttypedef)\].

<a id="listopsitemeventspaginator"></a>

## ListOpsItemEventsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_ops_item_events")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListOpsItemEventsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListOpsItemEventsPaginator = client.get_paginator("list_ops_item_events")
```

Boto3 documentation:
[SSM.Paginator.ListOpsItemEvents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemEvents)

Arguments for `ListOpsItemEventsPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[OpsItemEventFilterTypeDef](./type_defs.md#opsitemeventfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOpsItemEventsPaginator.paginate` returns
`_PageIterator`\[[ListOpsItemEventsResponseTypeDef](./type_defs.md#listopsitemeventsresponsetypedef)\].

<a id="listopsitemrelateditemspaginator"></a>

## ListOpsItemRelatedItemsPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_ops_item_related_items")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListOpsItemRelatedItemsPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListOpsItemRelatedItemsPaginator = client.get_paginator("list_ops_item_related_items")
```

Boto3 documentation:
[SSM.Paginator.ListOpsItemRelatedItems](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemRelatedItems)

Arguments for `ListOpsItemRelatedItemsPaginator.paginate` method:

- `OpsItemId`: `str`
- `Filters`:
  `Sequence`\[[OpsItemRelatedItemsFilterTypeDef](./type_defs.md#opsitemrelateditemsfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOpsItemRelatedItemsPaginator.paginate` returns
`_PageIterator`\[[ListOpsItemRelatedItemsResponseTypeDef](./type_defs.md#listopsitemrelateditemsresponsetypedef)\].

<a id="listopsmetadatapaginator"></a>

## ListOpsMetadataPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_ops_metadata")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListOpsMetadataPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListOpsMetadataPaginator = client.get_paginator("list_ops_metadata")
```

Boto3 documentation:
[SSM.Paginator.ListOpsMetadata](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsMetadata)

Arguments for `ListOpsMetadataPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[OpsMetadataFilterTypeDef](./type_defs.md#opsmetadatafiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListOpsMetadataPaginator.paginate` returns
`_PageIterator`\[[ListOpsMetadataResultTypeDef](./type_defs.md#listopsmetadataresulttypedef)\].

<a id="listresourcecompliancesummariespaginator"></a>

## ListResourceComplianceSummariesPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_resource_compliance_summaries")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListResourceComplianceSummariesPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListResourceComplianceSummariesPaginator = client.get_paginator("list_resource_compliance_summaries")
```

Boto3 documentation:
[SSM.Paginator.ListResourceComplianceSummaries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceComplianceSummaries)

Arguments for `ListResourceComplianceSummariesPaginator.paginate` method:

- `Filters`:
  `Sequence`\[[ComplianceStringFilterTypeDef](./type_defs.md#compliancestringfiltertypedef)\]
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResourceComplianceSummariesPaginator.paginate` returns
`_PageIterator`\[[ListResourceComplianceSummariesResultTypeDef](./type_defs.md#listresourcecompliancesummariesresulttypedef)\].

<a id="listresourcedatasyncpaginator"></a>

## ListResourceDataSyncPaginator

Type annotations for
`session.create_client("ssm").get_paginator("list_resource_data_sync")`.

Can be used directly:

```python
from aiobotocore.session import get_session

from types_aiobotocore_ssm.paginator import ListResourceDataSyncPaginator

session = get_session()
async with session.create_client("ssm") as client:
    client: SSMClient
    paginator: ListResourceDataSyncPaginator = client.get_paginator("list_resource_data_sync")
```

Boto3 documentation:
[SSM.Paginator.ListResourceDataSync](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceDataSync)

Arguments for `ListResourceDataSyncPaginator.paginate` method:

- `SyncType`: `str`
- `PaginationConfig`:
  [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)

`ListResourceDataSyncPaginator.paginate` returns
`_PageIterator`\[[ListResourceDataSyncResultTypeDef](./type_defs.md#listresourcedatasyncresulttypedef)\].
