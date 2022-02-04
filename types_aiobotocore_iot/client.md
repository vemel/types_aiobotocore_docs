<a id="iotclient-for-aiobotocore-iot-module"></a>

# IoTClient for aiobotocore IoT module

> [Index](..) > [IoT](.) > IoTClient

Auto-generated documentation for
[IoT](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
type annotations stubs module
[types-aiobotocore-iot](https://pypi.org/project/types-aiobotocore-iot/).

- [IoTClient for aiobotocore IoT module](#iotclient-for-aiobotocore-iot-module)
  - [IoTClient](#iotclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_certificate_transfer](#accept_certificate_transfer)
    - [add_thing_to_billing_group](#add_thing_to_billing_group)
    - [add_thing_to_thing_group](#add_thing_to_thing_group)
    - [associate_targets_with_job](#associate_targets_with_job)
    - [attach_policy](#attach_policy)
    - [attach_principal_policy](#attach_principal_policy)
    - [attach_security_profile](#attach_security_profile)
    - [attach_thing_principal](#attach_thing_principal)
    - [can_paginate](#can_paginate)
    - [cancel_audit_mitigation_actions_task](#cancel_audit_mitigation_actions_task)
    - [cancel_audit_task](#cancel_audit_task)
    - [cancel_certificate_transfer](#cancel_certificate_transfer)
    - [cancel_detect_mitigation_actions_task](#cancel_detect_mitigation_actions_task)
    - [cancel_job](#cancel_job)
    - [cancel_job_execution](#cancel_job_execution)
    - [clear_default_authorizer](#clear_default_authorizer)
    - [confirm_topic_rule_destination](#confirm_topic_rule_destination)
    - [create_audit_suppression](#create_audit_suppression)
    - [create_authorizer](#create_authorizer)
    - [create_billing_group](#create_billing_group)
    - [create_certificate_from_csr](#create_certificate_from_csr)
    - [create_custom_metric](#create_custom_metric)
    - [create_dimension](#create_dimension)
    - [create_domain_configuration](#create_domain_configuration)
    - [create_dynamic_thing_group](#create_dynamic_thing_group)
    - [create_fleet_metric](#create_fleet_metric)
    - [create_job](#create_job)
    - [create_job_template](#create_job_template)
    - [create_keys_and_certificate](#create_keys_and_certificate)
    - [create_mitigation_action](#create_mitigation_action)
    - [create_ota_update](#create_ota_update)
    - [create_policy](#create_policy)
    - [create_policy_version](#create_policy_version)
    - [create_provisioning_claim](#create_provisioning_claim)
    - [create_provisioning_template](#create_provisioning_template)
    - [create_provisioning_template_version](#create_provisioning_template_version)
    - [create_role_alias](#create_role_alias)
    - [create_scheduled_audit](#create_scheduled_audit)
    - [create_security_profile](#create_security_profile)
    - [create_stream](#create_stream)
    - [create_thing](#create_thing)
    - [create_thing_group](#create_thing_group)
    - [create_thing_type](#create_thing_type)
    - [create_topic_rule](#create_topic_rule)
    - [create_topic_rule_destination](#create_topic_rule_destination)
    - [delete_account_audit_configuration](#delete_account_audit_configuration)
    - [delete_audit_suppression](#delete_audit_suppression)
    - [delete_authorizer](#delete_authorizer)
    - [delete_billing_group](#delete_billing_group)
    - [delete_ca_certificate](#delete_ca_certificate)
    - [delete_certificate](#delete_certificate)
    - [delete_custom_metric](#delete_custom_metric)
    - [delete_dimension](#delete_dimension)
    - [delete_domain_configuration](#delete_domain_configuration)
    - [delete_dynamic_thing_group](#delete_dynamic_thing_group)
    - [delete_fleet_metric](#delete_fleet_metric)
    - [delete_job](#delete_job)
    - [delete_job_execution](#delete_job_execution)
    - [delete_job_template](#delete_job_template)
    - [delete_mitigation_action](#delete_mitigation_action)
    - [delete_ota_update](#delete_ota_update)
    - [delete_policy](#delete_policy)
    - [delete_policy_version](#delete_policy_version)
    - [delete_provisioning_template](#delete_provisioning_template)
    - [delete_provisioning_template_version](#delete_provisioning_template_version)
    - [delete_registration_code](#delete_registration_code)
    - [delete_role_alias](#delete_role_alias)
    - [delete_scheduled_audit](#delete_scheduled_audit)
    - [delete_security_profile](#delete_security_profile)
    - [delete_stream](#delete_stream)
    - [delete_thing](#delete_thing)
    - [delete_thing_group](#delete_thing_group)
    - [delete_thing_type](#delete_thing_type)
    - [delete_topic_rule](#delete_topic_rule)
    - [delete_topic_rule_destination](#delete_topic_rule_destination)
    - [delete_v2_logging_level](#delete_v2_logging_level)
    - [deprecate_thing_type](#deprecate_thing_type)
    - [describe_account_audit_configuration](#describe_account_audit_configuration)
    - [describe_audit_finding](#describe_audit_finding)
    - [describe_audit_mitigation_actions_task](#describe_audit_mitigation_actions_task)
    - [describe_audit_suppression](#describe_audit_suppression)
    - [describe_audit_task](#describe_audit_task)
    - [describe_authorizer](#describe_authorizer)
    - [describe_billing_group](#describe_billing_group)
    - [describe_ca_certificate](#describe_ca_certificate)
    - [describe_certificate](#describe_certificate)
    - [describe_custom_metric](#describe_custom_metric)
    - [describe_default_authorizer](#describe_default_authorizer)
    - [describe_detect_mitigation_actions_task](#describe_detect_mitigation_actions_task)
    - [describe_dimension](#describe_dimension)
    - [describe_domain_configuration](#describe_domain_configuration)
    - [describe_endpoint](#describe_endpoint)
    - [describe_event_configurations](#describe_event_configurations)
    - [describe_fleet_metric](#describe_fleet_metric)
    - [describe_index](#describe_index)
    - [describe_job](#describe_job)
    - [describe_job_execution](#describe_job_execution)
    - [describe_job_template](#describe_job_template)
    - [describe_managed_job_template](#describe_managed_job_template)
    - [describe_mitigation_action](#describe_mitigation_action)
    - [describe_provisioning_template](#describe_provisioning_template)
    - [describe_provisioning_template_version](#describe_provisioning_template_version)
    - [describe_role_alias](#describe_role_alias)
    - [describe_scheduled_audit](#describe_scheduled_audit)
    - [describe_security_profile](#describe_security_profile)
    - [describe_stream](#describe_stream)
    - [describe_thing](#describe_thing)
    - [describe_thing_group](#describe_thing_group)
    - [describe_thing_registration_task](#describe_thing_registration_task)
    - [describe_thing_type](#describe_thing_type)
    - [detach_policy](#detach_policy)
    - [detach_principal_policy](#detach_principal_policy)
    - [detach_security_profile](#detach_security_profile)
    - [detach_thing_principal](#detach_thing_principal)
    - [disable_topic_rule](#disable_topic_rule)
    - [enable_topic_rule](#enable_topic_rule)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_behavior_model_training_summaries](#get_behavior_model_training_summaries)
    - [get_buckets_aggregation](#get_buckets_aggregation)
    - [get_cardinality](#get_cardinality)
    - [get_effective_policies](#get_effective_policies)
    - [get_indexing_configuration](#get_indexing_configuration)
    - [get_job_document](#get_job_document)
    - [get_logging_options](#get_logging_options)
    - [get_ota_update](#get_ota_update)
    - [get_percentiles](#get_percentiles)
    - [get_policy](#get_policy)
    - [get_policy_version](#get_policy_version)
    - [get_registration_code](#get_registration_code)
    - [get_statistics](#get_statistics)
    - [get_topic_rule](#get_topic_rule)
    - [get_topic_rule_destination](#get_topic_rule_destination)
    - [get_v2_logging_options](#get_v2_logging_options)
    - [list_active_violations](#list_active_violations)
    - [list_attached_policies](#list_attached_policies)
    - [list_audit_findings](#list_audit_findings)
    - [list_audit_mitigation_actions_executions](#list_audit_mitigation_actions_executions)
    - [list_audit_mitigation_actions_tasks](#list_audit_mitigation_actions_tasks)
    - [list_audit_suppressions](#list_audit_suppressions)
    - [list_audit_tasks](#list_audit_tasks)
    - [list_authorizers](#list_authorizers)
    - [list_billing_groups](#list_billing_groups)
    - [list_ca_certificates](#list_ca_certificates)
    - [list_certificates](#list_certificates)
    - [list_certificates_by_ca](#list_certificates_by_ca)
    - [list_custom_metrics](#list_custom_metrics)
    - [list_detect_mitigation_actions_executions](#list_detect_mitigation_actions_executions)
    - [list_detect_mitigation_actions_tasks](#list_detect_mitigation_actions_tasks)
    - [list_dimensions](#list_dimensions)
    - [list_domain_configurations](#list_domain_configurations)
    - [list_fleet_metrics](#list_fleet_metrics)
    - [list_indices](#list_indices)
    - [list_job_executions_for_job](#list_job_executions_for_job)
    - [list_job_executions_for_thing](#list_job_executions_for_thing)
    - [list_job_templates](#list_job_templates)
    - [list_jobs](#list_jobs)
    - [list_managed_job_templates](#list_managed_job_templates)
    - [list_mitigation_actions](#list_mitigation_actions)
    - [list_ota_updates](#list_ota_updates)
    - [list_outgoing_certificates](#list_outgoing_certificates)
    - [list_policies](#list_policies)
    - [list_policy_principals](#list_policy_principals)
    - [list_policy_versions](#list_policy_versions)
    - [list_principal_policies](#list_principal_policies)
    - [list_principal_things](#list_principal_things)
    - [list_provisioning_template_versions](#list_provisioning_template_versions)
    - [list_provisioning_templates](#list_provisioning_templates)
    - [list_role_aliases](#list_role_aliases)
    - [list_scheduled_audits](#list_scheduled_audits)
    - [list_security_profiles](#list_security_profiles)
    - [list_security_profiles_for_target](#list_security_profiles_for_target)
    - [list_streams](#list_streams)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [list_targets_for_policy](#list_targets_for_policy)
    - [list_targets_for_security_profile](#list_targets_for_security_profile)
    - [list_thing_groups](#list_thing_groups)
    - [list_thing_groups_for_thing](#list_thing_groups_for_thing)
    - [list_thing_principals](#list_thing_principals)
    - [list_thing_registration_task_reports](#list_thing_registration_task_reports)
    - [list_thing_registration_tasks](#list_thing_registration_tasks)
    - [list_thing_types](#list_thing_types)
    - [list_things](#list_things)
    - [list_things_in_billing_group](#list_things_in_billing_group)
    - [list_things_in_thing_group](#list_things_in_thing_group)
    - [list_topic_rule_destinations](#list_topic_rule_destinations)
    - [list_topic_rules](#list_topic_rules)
    - [list_v2_logging_levels](#list_v2_logging_levels)
    - [list_violation_events](#list_violation_events)
    - [put_verification_state_on_violation](#put_verification_state_on_violation)
    - [register_ca_certificate](#register_ca_certificate)
    - [register_certificate](#register_certificate)
    - [register_certificate_without_ca](#register_certificate_without_ca)
    - [register_thing](#register_thing)
    - [reject_certificate_transfer](#reject_certificate_transfer)
    - [remove_thing_from_billing_group](#remove_thing_from_billing_group)
    - [remove_thing_from_thing_group](#remove_thing_from_thing_group)
    - [replace_topic_rule](#replace_topic_rule)
    - [search_index](#search_index)
    - [set_default_authorizer](#set_default_authorizer)
    - [set_default_policy_version](#set_default_policy_version)
    - [set_logging_options](#set_logging_options)
    - [set_v2_logging_level](#set_v2_logging_level)
    - [set_v2_logging_options](#set_v2_logging_options)
    - [start_audit_mitigation_actions_task](#start_audit_mitigation_actions_task)
    - [start_detect_mitigation_actions_task](#start_detect_mitigation_actions_task)
    - [start_on_demand_audit_task](#start_on_demand_audit_task)
    - [start_thing_registration_task](#start_thing_registration_task)
    - [stop_thing_registration_task](#stop_thing_registration_task)
    - [tag_resource](#tag_resource)
    - [test_authorization](#test_authorization)
    - [test_invoke_authorizer](#test_invoke_authorizer)
    - [transfer_certificate](#transfer_certificate)
    - [untag_resource](#untag_resource)
    - [update_account_audit_configuration](#update_account_audit_configuration)
    - [update_audit_suppression](#update_audit_suppression)
    - [update_authorizer](#update_authorizer)
    - [update_billing_group](#update_billing_group)
    - [update_ca_certificate](#update_ca_certificate)
    - [update_certificate](#update_certificate)
    - [update_custom_metric](#update_custom_metric)
    - [update_dimension](#update_dimension)
    - [update_domain_configuration](#update_domain_configuration)
    - [update_dynamic_thing_group](#update_dynamic_thing_group)
    - [update_event_configurations](#update_event_configurations)
    - [update_fleet_metric](#update_fleet_metric)
    - [update_indexing_configuration](#update_indexing_configuration)
    - [update_job](#update_job)
    - [update_mitigation_action](#update_mitigation_action)
    - [update_provisioning_template](#update_provisioning_template)
    - [update_role_alias](#update_role_alias)
    - [update_scheduled_audit](#update_scheduled_audit)
    - [update_security_profile](#update_security_profile)
    - [update_stream](#update_stream)
    - [update_thing](#update_thing)
    - [update_thing_group](#update_thing_group)
    - [update_thing_groups_for_thing](#update_thing_groups_for_thing)
    - [update_topic_rule_destination](#update_topic_rule_destination)
    - [validate_security_profile_behaviors](#validate_security_profile_behaviors)
    - [get_paginator](#get_paginator)

<a id="iotclient"></a>

## IoTClient

Type annotations for `aiobotocore.create_client("iot")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_iot.client import IoTClient

def get_iot_client() -> IoTClient:
    return Session().client("iot")
```

Boto3 documentation:
[IoT.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_iot.client import Exceptions

def handle_error(exc: Exceptions.CertificateConflictException) -> None:
    ...
```

Exceptions:

- `Exceptions.CertificateConflictException`
- `Exceptions.CertificateStateException`
- `Exceptions.CertificateValidationException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.ConflictingResourceUpdateException`
- `Exceptions.DeleteConflictException`
- `Exceptions.IndexNotReadyException`
- `Exceptions.InternalException`
- `Exceptions.InternalFailureException`
- `Exceptions.InternalServerException`
- `Exceptions.InvalidAggregationException`
- `Exceptions.InvalidQueryException`
- `Exceptions.InvalidRequestException`
- `Exceptions.InvalidResponseException`
- `Exceptions.InvalidStateTransitionException`
- `Exceptions.LimitExceededException`
- `Exceptions.MalformedPolicyException`
- `Exceptions.NotConfiguredException`
- `Exceptions.RegistrationCodeValidationException`
- `Exceptions.ResourceAlreadyExistsException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ResourceRegistrationFailureException`
- `Exceptions.ServiceUnavailableException`
- `Exceptions.SqlParseException`
- `Exceptions.TaskAlreadyExistsException`
- `Exceptions.ThrottlingException`
- `Exceptions.TransferAlreadyCompletedException`
- `Exceptions.TransferConflictException`
- `Exceptions.UnauthorizedException`
- `Exceptions.VersionConflictException`
- `Exceptions.VersionsLimitExceededException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

IoTClient exceptions.

Type annotations for `aiobotocore.create_client("iot").exceptions` method.

Boto3 documentation:
[IoT.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_certificate_transfer"></a>

### accept_certificate_transfer

Accepts a pending certificate transfer.

Type annotations for
`aiobotocore.create_client("iot").accept_certificate_transfer` method.

Boto3 documentation:
[IoT.Client.accept_certificate_transfer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.accept_certificate_transfer)

Asynchronous method. Use `await accept_certificate_transfer(...)` for a
synchronous call.

Arguments mapping described in
[AcceptCertificateTransferRequestRequestTypeDef](./type_defs.md#acceptcertificatetransferrequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `setAsActive`: `bool`

<a id="add_thing_to_billing_group"></a>

### add_thing_to_billing_group

Adds a thing to a billing group.

Type annotations for
`aiobotocore.create_client("iot").add_thing_to_billing_group` method.

Boto3 documentation:
[IoT.Client.add_thing_to_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.add_thing_to_billing_group)

Asynchronous method. Use `await add_thing_to_billing_group(...)` for a
synchronous call.

Arguments mapping described in
[AddThingToBillingGroupRequestRequestTypeDef](./type_defs.md#addthingtobillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str`
- `billingGroupArn`: `str`
- `thingName`: `str`
- `thingArn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="add_thing_to_thing_group"></a>

### add_thing_to_thing_group

Adds a thing to a thing group.

Type annotations for
`aiobotocore.create_client("iot").add_thing_to_thing_group` method.

Boto3 documentation:
[IoT.Client.add_thing_to_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.add_thing_to_thing_group)

Asynchronous method. Use `await add_thing_to_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[AddThingToThingGroupRequestRequestTypeDef](./type_defs.md#addthingtothinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str`
- `thingGroupArn`: `str`
- `thingName`: `str`
- `thingArn`: `str`
- `overrideDynamicGroups`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="associate_targets_with_job"></a>

### associate_targets_with_job

Associates a group with a continuous job.

Type annotations for
`aiobotocore.create_client("iot").associate_targets_with_job` method.

Boto3 documentation:
[IoT.Client.associate_targets_with_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.associate_targets_with_job)

Asynchronous method. Use `await associate_targets_with_job(...)` for a
synchronous call.

Arguments mapping described in
[AssociateTargetsWithJobRequestRequestTypeDef](./type_defs.md#associatetargetswithjobrequestrequesttypedef).

Keyword-only arguments:

- `targets`: `Sequence`\[`str`\] *(required)*
- `jobId`: `str` *(required)*
- `comment`: `str`
- `namespaceId`: `str`

Returns a `Coroutine` for
[AssociateTargetsWithJobResponseTypeDef](./type_defs.md#associatetargetswithjobresponsetypedef).

<a id="attach_policy"></a>

### attach_policy

Attaches the specified policy to the specified principal (certificate or other
credential).

Type annotations for `aiobotocore.create_client("iot").attach_policy` method.

Boto3 documentation:
[IoT.Client.attach_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.attach_policy)

Asynchronous method. Use `await attach_policy(...)` for a synchronous call.

Arguments mapping described in
[AttachPolicyRequestRequestTypeDef](./type_defs.md#attachpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `target`: `str` *(required)*

<a id="attach_principal_policy"></a>

### attach_principal_policy

Attaches the specified policy to the specified principal (certificate or other
credential).

Type annotations for `aiobotocore.create_client("iot").attach_principal_policy`
method.

Boto3 documentation:
[IoT.Client.attach_principal_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.attach_principal_policy)

Asynchronous method. Use `await attach_principal_policy(...)` for a synchronous
call.

Arguments mapping described in
[AttachPrincipalPolicyRequestRequestTypeDef](./type_defs.md#attachprincipalpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `principal`: `str` *(required)*

<a id="attach_security_profile"></a>

### attach_security_profile

Associates a Device Defender security profile with a thing group or this
account.

Type annotations for `aiobotocore.create_client("iot").attach_security_profile`
method.

Boto3 documentation:
[IoT.Client.attach_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.attach_security_profile)

Asynchronous method. Use `await attach_security_profile(...)` for a synchronous
call.

Arguments mapping described in
[AttachSecurityProfileRequestRequestTypeDef](./type_defs.md#attachsecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `securityProfileTargetArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="attach_thing_principal"></a>

### attach_thing_principal

Attaches the specified principal to the specified thing.

Type annotations for `aiobotocore.create_client("iot").attach_thing_principal`
method.

Boto3 documentation:
[IoT.Client.attach_thing_principal](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.attach_thing_principal)

Asynchronous method. Use `await attach_thing_principal(...)` for a synchronous
call.

Arguments mapping described in
[AttachThingPrincipalRequestRequestTypeDef](./type_defs.md#attachthingprincipalrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `principal`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("iot").can_paginate` method.

Boto3 documentation:
[IoT.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_audit_mitigation_actions_task"></a>

### cancel_audit_mitigation_actions_task

Cancels a mitigation action task that is in progress.

Type annotations for
`aiobotocore.create_client("iot").cancel_audit_mitigation_actions_task` method.

Boto3 documentation:
[IoT.Client.cancel_audit_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_audit_mitigation_actions_task)

Asynchronous method. Use `await cancel_audit_mitigation_actions_task(...)` for
a synchronous call.

Arguments mapping described in
[CancelAuditMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#cancelauditmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="cancel_audit_task"></a>

### cancel_audit_task

Cancels an audit that is in progress.

Type annotations for `aiobotocore.create_client("iot").cancel_audit_task`
method.

Boto3 documentation:
[IoT.Client.cancel_audit_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_audit_task)

Asynchronous method. Use `await cancel_audit_task(...)` for a synchronous call.

Arguments mapping described in
[CancelAuditTaskRequestRequestTypeDef](./type_defs.md#cancelaudittaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="cancel_certificate_transfer"></a>

### cancel_certificate_transfer

Cancels a pending transfer for the specified certificate.

Type annotations for
`aiobotocore.create_client("iot").cancel_certificate_transfer` method.

Boto3 documentation:
[IoT.Client.cancel_certificate_transfer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_certificate_transfer)

Asynchronous method. Use `await cancel_certificate_transfer(...)` for a
synchronous call.

Arguments mapping described in
[CancelCertificateTransferRequestRequestTypeDef](./type_defs.md#cancelcertificatetransferrequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*

<a id="cancel_detect_mitigation_actions_task"></a>

### cancel_detect_mitigation_actions_task

Cancels a Device Defender ML Detect mitigation action.

Type annotations for
`aiobotocore.create_client("iot").cancel_detect_mitigation_actions_task`
method.

Boto3 documentation:
[IoT.Client.cancel_detect_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_detect_mitigation_actions_task)

Asynchronous method. Use `await cancel_detect_mitigation_actions_task(...)` for
a synchronous call.

Arguments mapping described in
[CancelDetectMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#canceldetectmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="cancel_job"></a>

### cancel_job

Cancels a job.

Type annotations for `aiobotocore.create_client("iot").cancel_job` method.

Boto3 documentation:
[IoT.Client.cancel_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_job)

Asynchronous method. Use `await cancel_job(...)` for a synchronous call.

Arguments mapping described in
[CancelJobRequestRequestTypeDef](./type_defs.md#canceljobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `reasonCode`: `str`
- `comment`: `str`
- `force`: `bool`

Returns a `Coroutine` for
[CancelJobResponseTypeDef](./type_defs.md#canceljobresponsetypedef).

<a id="cancel_job_execution"></a>

### cancel_job_execution

Cancels the execution of a job for a given thing.

Type annotations for `aiobotocore.create_client("iot").cancel_job_execution`
method.

Boto3 documentation:
[IoT.Client.cancel_job_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.cancel_job_execution)

Asynchronous method. Use `await cancel_job_execution(...)` for a synchronous
call.

Arguments mapping described in
[CancelJobExecutionRequestRequestTypeDef](./type_defs.md#canceljobexecutionrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `thingName`: `str` *(required)*
- `force`: `bool`
- `expectedVersion`: `int`
- `statusDetails`: `Mapping`\[`str`, `str`\]

<a id="clear_default_authorizer"></a>

### clear_default_authorizer

Clears the default authorizer.

Type annotations for
`aiobotocore.create_client("iot").clear_default_authorizer` method.

Boto3 documentation:
[IoT.Client.clear_default_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.clear_default_authorizer)

Asynchronous method. Use `await clear_default_authorizer(...)` for a
synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="confirm_topic_rule_destination"></a>

### confirm_topic_rule_destination

Confirms a topic rule destination.

Type annotations for
`aiobotocore.create_client("iot").confirm_topic_rule_destination` method.

Boto3 documentation:
[IoT.Client.confirm_topic_rule_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.confirm_topic_rule_destination)

Asynchronous method. Use `await confirm_topic_rule_destination(...)` for a
synchronous call.

Arguments mapping described in
[ConfirmTopicRuleDestinationRequestRequestTypeDef](./type_defs.md#confirmtopicruledestinationrequestrequesttypedef).

Keyword-only arguments:

- `confirmationToken`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_audit_suppression"></a>

### create_audit_suppression

Creates a Device Defender audit suppression.

Type annotations for
`aiobotocore.create_client("iot").create_audit_suppression` method.

Boto3 documentation:
[IoT.Client.create_audit_suppression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_audit_suppression)

Asynchronous method. Use `await create_audit_suppression(...)` for a
synchronous call.

Arguments mapping described in
[CreateAuditSuppressionRequestRequestTypeDef](./type_defs.md#createauditsuppressionrequestrequesttypedef).

Keyword-only arguments:

- `checkName`: `str` *(required)*
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
  *(required)*
- `clientRequestToken`: `str` *(required)*
- `expirationDate`: `Union`\[`datetime`, `str`\]
- `suppressIndefinitely`: `bool`
- `description`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="create_authorizer"></a>

### create_authorizer

Creates an authorizer.

Type annotations for `aiobotocore.create_client("iot").create_authorizer`
method.

Boto3 documentation:
[IoT.Client.create_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_authorizer)

Asynchronous method. Use `await create_authorizer(...)` for a synchronous call.

Arguments mapping described in
[CreateAuthorizerRequestRequestTypeDef](./type_defs.md#createauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*
- `authorizerFunctionArn`: `str` *(required)*
- `tokenKeyName`: `str`
- `tokenSigningPublicKeys`: `Mapping`\[`str`, `str`\]
- `status`: [AuthorizerStatusType](./literals.md#authorizerstatustype)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `signingDisabled`: `bool`
- `enableCachingForHttp`: `bool`

Returns a `Coroutine` for
[CreateAuthorizerResponseTypeDef](./type_defs.md#createauthorizerresponsetypedef).

<a id="create_billing_group"></a>

### create_billing_group

Creates a billing group.

Type annotations for `aiobotocore.create_client("iot").create_billing_group`
method.

Boto3 documentation:
[IoT.Client.create_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_billing_group)

Asynchronous method. Use `await create_billing_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateBillingGroupRequestRequestTypeDef](./type_defs.md#createbillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str` *(required)*
- `billingGroupProperties`:
  [BillingGroupPropertiesTypeDef](./type_defs.md#billinggrouppropertiestypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateBillingGroupResponseTypeDef](./type_defs.md#createbillinggroupresponsetypedef).

<a id="create_certificate_from_csr"></a>

### create_certificate_from_csr

Creates an X.509 certificate using the specified certificate signing request.

Type annotations for
`aiobotocore.create_client("iot").create_certificate_from_csr` method.

Boto3 documentation:
[IoT.Client.create_certificate_from_csr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_certificate_from_csr)

Asynchronous method. Use `await create_certificate_from_csr(...)` for a
synchronous call.

Arguments mapping described in
[CreateCertificateFromCsrRequestRequestTypeDef](./type_defs.md#createcertificatefromcsrrequestrequesttypedef).

Keyword-only arguments:

- `certificateSigningRequest`: `str` *(required)*
- `setAsActive`: `bool`

Returns a `Coroutine` for
[CreateCertificateFromCsrResponseTypeDef](./type_defs.md#createcertificatefromcsrresponsetypedef).

<a id="create_custom_metric"></a>

### create_custom_metric

Use this API to define a Custom Metric published by your devices to Device
Defender.

Type annotations for `aiobotocore.create_client("iot").create_custom_metric`
method.

Boto3 documentation:
[IoT.Client.create_custom_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_custom_metric)

Asynchronous method. Use `await create_custom_metric(...)` for a synchronous
call.

Arguments mapping described in
[CreateCustomMetricRequestRequestTypeDef](./type_defs.md#createcustommetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*
- `metricType`: [CustomMetricTypeType](./literals.md#custommetrictypetype)
  *(required)*
- `clientRequestToken`: `str` *(required)*
- `displayName`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateCustomMetricResponseTypeDef](./type_defs.md#createcustommetricresponsetypedef).

<a id="create_dimension"></a>

### create_dimension

Create a dimension that you can use to limit the scope of a metric used in a
security profile for IoT Device Defender.

Type annotations for `aiobotocore.create_client("iot").create_dimension`
method.

Boto3 documentation:
[IoT.Client.create_dimension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_dimension)

Asynchronous method. Use `await create_dimension(...)` for a synchronous call.

Arguments mapping described in
[CreateDimensionRequestRequestTypeDef](./type_defs.md#createdimensionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `type`: `Literal['TOPIC_FILTER']` (see
  [DimensionTypeType](./literals.md#dimensiontypetype)) *(required)*
- `stringValues`: `Sequence`\[`str`\] *(required)*
- `clientRequestToken`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDimensionResponseTypeDef](./type_defs.md#createdimensionresponsetypedef).

<a id="create_domain_configuration"></a>

### create_domain_configuration

Creates a domain configuration.

Type annotations for
`aiobotocore.create_client("iot").create_domain_configuration` method.

Boto3 documentation:
[IoT.Client.create_domain_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_domain_configuration)

Asynchronous method. Use `await create_domain_configuration(...)` for a
synchronous call.

Arguments mapping described in
[CreateDomainConfigurationRequestRequestTypeDef](./type_defs.md#createdomainconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `domainConfigurationName`: `str` *(required)*
- `domainName`: `str`
- `serverCertificateArns`: `Sequence`\[`str`\]
- `validationCertificateArn`: `str`
- `authorizerConfig`:
  [AuthorizerConfigTypeDef](./type_defs.md#authorizerconfigtypedef)
- `serviceType`: [ServiceTypeType](./literals.md#servicetypetype)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDomainConfigurationResponseTypeDef](./type_defs.md#createdomainconfigurationresponsetypedef).

<a id="create_dynamic_thing_group"></a>

### create_dynamic_thing_group

Creates a dynamic thing group.

Type annotations for
`aiobotocore.create_client("iot").create_dynamic_thing_group` method.

Boto3 documentation:
[IoT.Client.create_dynamic_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_dynamic_thing_group)

Asynchronous method. Use `await create_dynamic_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[CreateDynamicThingGroupRequestRequestTypeDef](./type_defs.md#createdynamicthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `queryString`: `str` *(required)*
- `thingGroupProperties`:
  [ThingGroupPropertiesTypeDef](./type_defs.md#thinggrouppropertiestypedef)
- `indexName`: `str`
- `queryVersion`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateDynamicThingGroupResponseTypeDef](./type_defs.md#createdynamicthinggroupresponsetypedef).

<a id="create_fleet_metric"></a>

### create_fleet_metric

Creates a fleet metric.

Type annotations for `aiobotocore.create_client("iot").create_fleet_metric`
method.

Boto3 documentation:
[IoT.Client.create_fleet_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_fleet_metric)

Asynchronous method. Use `await create_fleet_metric(...)` for a synchronous
call.

Arguments mapping described in
[CreateFleetMetricRequestRequestTypeDef](./type_defs.md#createfleetmetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*
- `queryString`: `str` *(required)*
- `aggregationType`:
  [AggregationTypeTypeDef](./type_defs.md#aggregationtypetypedef) *(required)*
- `period`: `int` *(required)*
- `aggregationField`: `str` *(required)*
- `description`: `str`
- `queryVersion`: `str`
- `indexName`: `str`
- `unit`: [FleetMetricUnitType](./literals.md#fleetmetricunittype)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateFleetMetricResponseTypeDef](./type_defs.md#createfleetmetricresponsetypedef).

<a id="create_job"></a>

### create_job

Creates a job.

Type annotations for `aiobotocore.create_client("iot").create_job` method.

Boto3 documentation:
[IoT.Client.create_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job)

Asynchronous method. Use `await create_job(...)` for a synchronous call.

Arguments mapping described in
[CreateJobRequestRequestTypeDef](./type_defs.md#createjobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `targets`: `Sequence`\[`str`\] *(required)*
- `documentSource`: `str`
- `document`: `str`
- `description`: `str`
- `presignedUrlConfig`:
  [PresignedUrlConfigTypeDef](./type_defs.md#presignedurlconfigtypedef)
- `targetSelection`: [TargetSelectionType](./literals.md#targetselectiontype)
- `jobExecutionsRolloutConfig`:
  [JobExecutionsRolloutConfigTypeDef](./type_defs.md#jobexecutionsrolloutconfigtypedef)
- `abortConfig`: [AbortConfigTypeDef](./type_defs.md#abortconfigtypedef)
- `timeoutConfig`: [TimeoutConfigTypeDef](./type_defs.md#timeoutconfigtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `namespaceId`: `str`
- `jobTemplateArn`: `str`
- `documentParameters`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[CreateJobResponseTypeDef](./type_defs.md#createjobresponsetypedef).

<a id="create_job_template"></a>

### create_job_template

Creates a job template.

Type annotations for `aiobotocore.create_client("iot").create_job_template`
method.

Boto3 documentation:
[IoT.Client.create_job_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job_template)

Asynchronous method. Use `await create_job_template(...)` for a synchronous
call.

Arguments mapping described in
[CreateJobTemplateRequestRequestTypeDef](./type_defs.md#createjobtemplaterequestrequesttypedef).

Keyword-only arguments:

- `jobTemplateId`: `str` *(required)*
- `description`: `str` *(required)*
- `jobArn`: `str`
- `documentSource`: `str`
- `document`: `str`
- `presignedUrlConfig`:
  [PresignedUrlConfigTypeDef](./type_defs.md#presignedurlconfigtypedef)
- `jobExecutionsRolloutConfig`:
  [JobExecutionsRolloutConfigTypeDef](./type_defs.md#jobexecutionsrolloutconfigtypedef)
- `abortConfig`: [AbortConfigTypeDef](./type_defs.md#abortconfigtypedef)
- `timeoutConfig`: [TimeoutConfigTypeDef](./type_defs.md#timeoutconfigtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateJobTemplateResponseTypeDef](./type_defs.md#createjobtemplateresponsetypedef).

<a id="create_keys_and_certificate"></a>

### create_keys_and_certificate

Creates a 2048-bit RSA key pair and issues an X.509 certificate using the
issued public key.

Type annotations for
`aiobotocore.create_client("iot").create_keys_and_certificate` method.

Boto3 documentation:
[IoT.Client.create_keys_and_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_keys_and_certificate)

Asynchronous method. Use `await create_keys_and_certificate(...)` for a
synchronous call.

Arguments mapping described in
[CreateKeysAndCertificateRequestRequestTypeDef](./type_defs.md#createkeysandcertificaterequestrequesttypedef).

Keyword-only arguments:

- `setAsActive`: `bool`

Returns a `Coroutine` for
[CreateKeysAndCertificateResponseTypeDef](./type_defs.md#createkeysandcertificateresponsetypedef).

<a id="create_mitigation_action"></a>

### create_mitigation_action

Defines an action that can be applied to audit findings by using
StartAuditMitigationActionsTask.

Type annotations for
`aiobotocore.create_client("iot").create_mitigation_action` method.

Boto3 documentation:
[IoT.Client.create_mitigation_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_mitigation_action)

Asynchronous method. Use `await create_mitigation_action(...)` for a
synchronous call.

Arguments mapping described in
[CreateMitigationActionRequestRequestTypeDef](./type_defs.md#createmitigationactionrequestrequesttypedef).

Keyword-only arguments:

- `actionName`: `str` *(required)*
- `roleArn`: `str` *(required)*
- `actionParams`:
  [MitigationActionParamsTypeDef](./type_defs.md#mitigationactionparamstypedef)
  *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateMitigationActionResponseTypeDef](./type_defs.md#createmitigationactionresponsetypedef).

<a id="create_ota_update"></a>

### create_ota_update

Creates an IoT OTA update on a target group of things or groups.

Type annotations for `aiobotocore.create_client("iot").create_ota_update`
method.

Boto3 documentation:
[IoT.Client.create_ota_update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_ota_update)

Asynchronous method. Use `await create_ota_update(...)` for a synchronous call.

Arguments mapping described in
[CreateOTAUpdateRequestRequestTypeDef](./type_defs.md#createotaupdaterequestrequesttypedef).

Keyword-only arguments:

- `otaUpdateId`: `str` *(required)*
- `targets`: `Sequence`\[`str`\] *(required)*
- `files`:
  `Sequence`\[[OTAUpdateFileTypeDef](./type_defs.md#otaupdatefiletypedef)\]
  *(required)*
- `roleArn`: `str` *(required)*
- `description`: `str`
- `protocols`: `Sequence`\[[ProtocolType](./literals.md#protocoltype)\]
- `targetSelection`: [TargetSelectionType](./literals.md#targetselectiontype)
- `awsJobExecutionsRolloutConfig`:
  [AwsJobExecutionsRolloutConfigTypeDef](./type_defs.md#awsjobexecutionsrolloutconfigtypedef)
- `awsJobPresignedUrlConfig`:
  [AwsJobPresignedUrlConfigTypeDef](./type_defs.md#awsjobpresignedurlconfigtypedef)
- `awsJobAbortConfig`:
  [AwsJobAbortConfigTypeDef](./type_defs.md#awsjobabortconfigtypedef)
- `awsJobTimeoutConfig`:
  [AwsJobTimeoutConfigTypeDef](./type_defs.md#awsjobtimeoutconfigtypedef)
- `additionalParameters`: `Mapping`\[`str`, `str`\]
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateOTAUpdateResponseTypeDef](./type_defs.md#createotaupdateresponsetypedef).

<a id="create_policy"></a>

### create_policy

Creates an IoT policy.

Type annotations for `aiobotocore.create_client("iot").create_policy` method.

Boto3 documentation:
[IoT.Client.create_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_policy)

Asynchronous method. Use `await create_policy(...)` for a synchronous call.

Arguments mapping described in
[CreatePolicyRequestRequestTypeDef](./type_defs.md#createpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `policyDocument`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreatePolicyResponseTypeDef](./type_defs.md#createpolicyresponsetypedef).

<a id="create_policy_version"></a>

### create_policy_version

Creates a new version of the specified IoT policy.

Type annotations for `aiobotocore.create_client("iot").create_policy_version`
method.

Boto3 documentation:
[IoT.Client.create_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_policy_version)

Asynchronous method. Use `await create_policy_version(...)` for a synchronous
call.

Arguments mapping described in
[CreatePolicyVersionRequestRequestTypeDef](./type_defs.md#createpolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `policyDocument`: `str` *(required)*
- `setAsDefault`: `bool`

Returns a `Coroutine` for
[CreatePolicyVersionResponseTypeDef](./type_defs.md#createpolicyversionresponsetypedef).

<a id="create_provisioning_claim"></a>

### create_provisioning_claim

Creates a provisioning claim.

Type annotations for
`aiobotocore.create_client("iot").create_provisioning_claim` method.

Boto3 documentation:
[IoT.Client.create_provisioning_claim](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_provisioning_claim)

Asynchronous method. Use `await create_provisioning_claim(...)` for a
synchronous call.

Arguments mapping described in
[CreateProvisioningClaimRequestRequestTypeDef](./type_defs.md#createprovisioningclaimrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*

Returns a `Coroutine` for
[CreateProvisioningClaimResponseTypeDef](./type_defs.md#createprovisioningclaimresponsetypedef).

<a id="create_provisioning_template"></a>

### create_provisioning_template

Creates a fleet provisioning template.

Type annotations for
`aiobotocore.create_client("iot").create_provisioning_template` method.

Boto3 documentation:
[IoT.Client.create_provisioning_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_provisioning_template)

Asynchronous method. Use `await create_provisioning_template(...)` for a
synchronous call.

Arguments mapping described in
[CreateProvisioningTemplateRequestRequestTypeDef](./type_defs.md#createprovisioningtemplaterequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `templateBody`: `str` *(required)*
- `provisioningRoleArn`: `str` *(required)*
- `description`: `str`
- `enabled`: `bool`
- `preProvisioningHook`:
  [ProvisioningHookTypeDef](./type_defs.md#provisioninghooktypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateProvisioningTemplateResponseTypeDef](./type_defs.md#createprovisioningtemplateresponsetypedef).

<a id="create_provisioning_template_version"></a>

### create_provisioning_template_version

Creates a new version of a fleet provisioning template.

Type annotations for
`aiobotocore.create_client("iot").create_provisioning_template_version` method.

Boto3 documentation:
[IoT.Client.create_provisioning_template_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_provisioning_template_version)

Asynchronous method. Use `await create_provisioning_template_version(...)` for
a synchronous call.

Arguments mapping described in
[CreateProvisioningTemplateVersionRequestRequestTypeDef](./type_defs.md#createprovisioningtemplateversionrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `templateBody`: `str` *(required)*
- `setAsDefault`: `bool`

Returns a `Coroutine` for
[CreateProvisioningTemplateVersionResponseTypeDef](./type_defs.md#createprovisioningtemplateversionresponsetypedef).

<a id="create_role_alias"></a>

### create_role_alias

Creates a role alias.

Type annotations for `aiobotocore.create_client("iot").create_role_alias`
method.

Boto3 documentation:
[IoT.Client.create_role_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_role_alias)

Asynchronous method. Use `await create_role_alias(...)` for a synchronous call.

Arguments mapping described in
[CreateRoleAliasRequestRequestTypeDef](./type_defs.md#createrolealiasrequestrequesttypedef).

Keyword-only arguments:

- `roleAlias`: `str` *(required)*
- `roleArn`: `str` *(required)*
- `credentialDurationSeconds`: `int`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateRoleAliasResponseTypeDef](./type_defs.md#createrolealiasresponsetypedef).

<a id="create_scheduled_audit"></a>

### create_scheduled_audit

Creates a scheduled audit that is run at a specified time interval.

Type annotations for `aiobotocore.create_client("iot").create_scheduled_audit`
method.

Boto3 documentation:
[IoT.Client.create_scheduled_audit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_scheduled_audit)

Asynchronous method. Use `await create_scheduled_audit(...)` for a synchronous
call.

Arguments mapping described in
[CreateScheduledAuditRequestRequestTypeDef](./type_defs.md#createscheduledauditrequestrequesttypedef).

Keyword-only arguments:

- `frequency`: [AuditFrequencyType](./literals.md#auditfrequencytype)
  *(required)*
- `targetCheckNames`: `Sequence`\[`str`\] *(required)*
- `scheduledAuditName`: `str` *(required)*
- `dayOfMonth`: `str`
- `dayOfWeek`: [DayOfWeekType](./literals.md#dayofweektype)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateScheduledAuditResponseTypeDef](./type_defs.md#createscheduledauditresponsetypedef).

<a id="create_security_profile"></a>

### create_security_profile

Creates a Device Defender security profile.

Type annotations for `aiobotocore.create_client("iot").create_security_profile`
method.

Boto3 documentation:
[IoT.Client.create_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_security_profile)

Asynchronous method. Use `await create_security_profile(...)` for a synchronous
call.

Arguments mapping described in
[CreateSecurityProfileRequestRequestTypeDef](./type_defs.md#createsecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `securityProfileDescription`: `str`
- `behaviors`: `Sequence`\[[BehaviorTypeDef](./type_defs.md#behaviortypedef)\]
- `alertTargets`: `Mapping`\[`Literal['SNS']` (see
  [AlertTargetTypeType](./literals.md#alerttargettypetype)),
  [AlertTargetTypeDef](./type_defs.md#alerttargettypedef)\]
- `additionalMetricsToRetain`: `Sequence`\[`str`\]
- `additionalMetricsToRetainV2`:
  `Sequence`\[[MetricToRetainTypeDef](./type_defs.md#metrictoretaintypedef)\]
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateSecurityProfileResponseTypeDef](./type_defs.md#createsecurityprofileresponsetypedef).

<a id="create_stream"></a>

### create_stream

Creates a stream for delivering one or more large files in chunks over MQTT.

Type annotations for `aiobotocore.create_client("iot").create_stream` method.

Boto3 documentation:
[IoT.Client.create_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_stream)

Asynchronous method. Use `await create_stream(...)` for a synchronous call.

Arguments mapping described in
[CreateStreamRequestRequestTypeDef](./type_defs.md#createstreamrequestrequesttypedef).

Keyword-only arguments:

- `streamId`: `str` *(required)*
- `files`: `Sequence`\[[StreamFileTypeDef](./type_defs.md#streamfiletypedef)\]
  *(required)*
- `roleArn`: `str` *(required)*
- `description`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateStreamResponseTypeDef](./type_defs.md#createstreamresponsetypedef).

<a id="create_thing"></a>

### create_thing

Creates a thing record in the registry.

Type annotations for `aiobotocore.create_client("iot").create_thing` method.

Boto3 documentation:
[IoT.Client.create_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_thing)

Asynchronous method. Use `await create_thing(...)` for a synchronous call.

Arguments mapping described in
[CreateThingRequestRequestTypeDef](./type_defs.md#createthingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `thingTypeName`: `str`
- `attributePayload`:
  [AttributePayloadTypeDef](./type_defs.md#attributepayloadtypedef)
- `billingGroupName`: `str`

Returns a `Coroutine` for
[CreateThingResponseTypeDef](./type_defs.md#createthingresponsetypedef).

<a id="create_thing_group"></a>

### create_thing_group

Create a thing group.

Type annotations for `aiobotocore.create_client("iot").create_thing_group`
method.

Boto3 documentation:
[IoT.Client.create_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_thing_group)

Asynchronous method. Use `await create_thing_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateThingGroupRequestRequestTypeDef](./type_defs.md#createthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `parentGroupName`: `str`
- `thingGroupProperties`:
  [ThingGroupPropertiesTypeDef](./type_defs.md#thinggrouppropertiestypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateThingGroupResponseTypeDef](./type_defs.md#createthinggroupresponsetypedef).

<a id="create_thing_type"></a>

### create_thing_type

Creates a new thing type.

Type annotations for `aiobotocore.create_client("iot").create_thing_type`
method.

Boto3 documentation:
[IoT.Client.create_thing_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_thing_type)

Asynchronous method. Use `await create_thing_type(...)` for a synchronous call.

Arguments mapping described in
[CreateThingTypeRequestRequestTypeDef](./type_defs.md#createthingtyperequestrequesttypedef).

Keyword-only arguments:

- `thingTypeName`: `str` *(required)*
- `thingTypeProperties`:
  [ThingTypePropertiesTypeDef](./type_defs.md#thingtypepropertiestypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateThingTypeResponseTypeDef](./type_defs.md#createthingtyperesponsetypedef).

<a id="create_topic_rule"></a>

### create_topic_rule

.

Type annotations for `aiobotocore.create_client("iot").create_topic_rule`
method.

Boto3 documentation:
[IoT.Client.create_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_topic_rule)

Asynchronous method. Use `await create_topic_rule(...)` for a synchronous call.

Arguments mapping described in
[CreateTopicRuleRequestRequestTypeDef](./type_defs.md#createtopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*
- `topicRulePayload`:
  [TopicRulePayloadTypeDef](./type_defs.md#topicrulepayloadtypedef)
  *(required)*
- `tags`: `str`

<a id="create_topic_rule_destination"></a>

### create_topic_rule_destination

Creates a topic rule destination.

Type annotations for
`aiobotocore.create_client("iot").create_topic_rule_destination` method.

Boto3 documentation:
[IoT.Client.create_topic_rule_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_topic_rule_destination)

Asynchronous method. Use `await create_topic_rule_destination(...)` for a
synchronous call.

Arguments mapping described in
[CreateTopicRuleDestinationRequestRequestTypeDef](./type_defs.md#createtopicruledestinationrequestrequesttypedef).

Keyword-only arguments:

- `destinationConfiguration`:
  [TopicRuleDestinationConfigurationTypeDef](./type_defs.md#topicruledestinationconfigurationtypedef)
  *(required)*

Returns a `Coroutine` for
[CreateTopicRuleDestinationResponseTypeDef](./type_defs.md#createtopicruledestinationresponsetypedef).

<a id="delete_account_audit_configuration"></a>

### delete_account_audit_configuration

Restores the default settings for Device Defender audits for this account.

Type annotations for
`aiobotocore.create_client("iot").delete_account_audit_configuration` method.

Boto3 documentation:
[IoT.Client.delete_account_audit_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_account_audit_configuration)

Asynchronous method. Use `await delete_account_audit_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteAccountAuditConfigurationRequestRequestTypeDef](./type_defs.md#deleteaccountauditconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `deleteScheduledAudits`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_audit_suppression"></a>

### delete_audit_suppression

Deletes a Device Defender audit suppression.

Type annotations for
`aiobotocore.create_client("iot").delete_audit_suppression` method.

Boto3 documentation:
[IoT.Client.delete_audit_suppression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_audit_suppression)

Asynchronous method. Use `await delete_audit_suppression(...)` for a
synchronous call.

Arguments mapping described in
[DeleteAuditSuppressionRequestRequestTypeDef](./type_defs.md#deleteauditsuppressionrequestrequesttypedef).

Keyword-only arguments:

- `checkName`: `str` *(required)*
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_authorizer"></a>

### delete_authorizer

Deletes an authorizer.

Type annotations for `aiobotocore.create_client("iot").delete_authorizer`
method.

Boto3 documentation:
[IoT.Client.delete_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_authorizer)

Asynchronous method. Use `await delete_authorizer(...)` for a synchronous call.

Arguments mapping described in
[DeleteAuthorizerRequestRequestTypeDef](./type_defs.md#deleteauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_billing_group"></a>

### delete_billing_group

Deletes the billing group.

Type annotations for `aiobotocore.create_client("iot").delete_billing_group`
method.

Boto3 documentation:
[IoT.Client.delete_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_billing_group)

Asynchronous method. Use `await delete_billing_group(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBillingGroupRequestRequestTypeDef](./type_defs.md#deletebillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str` *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_ca_certificate"></a>

### delete_ca_certificate

Deletes a registered CA certificate.

Type annotations for `aiobotocore.create_client("iot").delete_ca_certificate`
method.

Boto3 documentation:
[IoT.Client.delete_ca_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_ca_certificate)

Asynchronous method. Use `await delete_ca_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCACertificateRequestRequestTypeDef](./type_defs.md#deletecacertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_certificate"></a>

### delete_certificate

Deletes the specified certificate.

Type annotations for `aiobotocore.create_client("iot").delete_certificate`
method.

Boto3 documentation:
[IoT.Client.delete_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_certificate)

Asynchronous method. Use `await delete_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCertificateRequestRequestTypeDef](./type_defs.md#deletecertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `forceDelete`: `bool`

<a id="delete_custom_metric"></a>

### delete_custom_metric

Deletes a Device Defender detect custom metric.

Type annotations for `aiobotocore.create_client("iot").delete_custom_metric`
method.

Boto3 documentation:
[IoT.Client.delete_custom_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_custom_metric)

Asynchronous method. Use `await delete_custom_metric(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCustomMetricRequestRequestTypeDef](./type_defs.md#deletecustommetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_dimension"></a>

### delete_dimension

Removes the specified dimension from your Amazon Web Services accounts.

Type annotations for `aiobotocore.create_client("iot").delete_dimension`
method.

Boto3 documentation:
[IoT.Client.delete_dimension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_dimension)

Asynchronous method. Use `await delete_dimension(...)` for a synchronous call.

Arguments mapping described in
[DeleteDimensionRequestRequestTypeDef](./type_defs.md#deletedimensionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_domain_configuration"></a>

### delete_domain_configuration

Deletes the specified domain configuration.

Type annotations for
`aiobotocore.create_client("iot").delete_domain_configuration` method.

Boto3 documentation:
[IoT.Client.delete_domain_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_domain_configuration)

Asynchronous method. Use `await delete_domain_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDomainConfigurationRequestRequestTypeDef](./type_defs.md#deletedomainconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `domainConfigurationName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_dynamic_thing_group"></a>

### delete_dynamic_thing_group

Deletes a dynamic thing group.

Type annotations for
`aiobotocore.create_client("iot").delete_dynamic_thing_group` method.

Boto3 documentation:
[IoT.Client.delete_dynamic_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_dynamic_thing_group)

Asynchronous method. Use `await delete_dynamic_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[DeleteDynamicThingGroupRequestRequestTypeDef](./type_defs.md#deletedynamicthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_fleet_metric"></a>

### delete_fleet_metric

Deletes the specified fleet metric.

Type annotations for `aiobotocore.create_client("iot").delete_fleet_metric`
method.

Boto3 documentation:
[IoT.Client.delete_fleet_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_fleet_metric)

Asynchronous method. Use `await delete_fleet_metric(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFleetMetricRequestRequestTypeDef](./type_defs.md#deletefleetmetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*
- `expectedVersion`: `int`

<a id="delete_job"></a>

### delete_job

Deletes a job and its related job executions.

Type annotations for `aiobotocore.create_client("iot").delete_job` method.

Boto3 documentation:
[IoT.Client.delete_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_job)

Asynchronous method. Use `await delete_job(...)` for a synchronous call.

Arguments mapping described in
[DeleteJobRequestRequestTypeDef](./type_defs.md#deletejobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `force`: `bool`
- `namespaceId`: `str`

<a id="delete_job_execution"></a>

### delete_job_execution

Deletes a job execution.

Type annotations for `aiobotocore.create_client("iot").delete_job_execution`
method.

Boto3 documentation:
[IoT.Client.delete_job_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_job_execution)

Asynchronous method. Use `await delete_job_execution(...)` for a synchronous
call.

Arguments mapping described in
[DeleteJobExecutionRequestRequestTypeDef](./type_defs.md#deletejobexecutionrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `thingName`: `str` *(required)*
- `executionNumber`: `int` *(required)*
- `force`: `bool`
- `namespaceId`: `str`

<a id="delete_job_template"></a>

### delete_job_template

Deletes the specified job template.

Type annotations for `aiobotocore.create_client("iot").delete_job_template`
method.

Boto3 documentation:
[IoT.Client.delete_job_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_job_template)

Asynchronous method. Use `await delete_job_template(...)` for a synchronous
call.

Arguments mapping described in
[DeleteJobTemplateRequestRequestTypeDef](./type_defs.md#deletejobtemplaterequestrequesttypedef).

Keyword-only arguments:

- `jobTemplateId`: `str` *(required)*

<a id="delete_mitigation_action"></a>

### delete_mitigation_action

Deletes a defined mitigation action from your Amazon Web Services accounts.

Type annotations for
`aiobotocore.create_client("iot").delete_mitigation_action` method.

Boto3 documentation:
[IoT.Client.delete_mitigation_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_mitigation_action)

Asynchronous method. Use `await delete_mitigation_action(...)` for a
synchronous call.

Arguments mapping described in
[DeleteMitigationActionRequestRequestTypeDef](./type_defs.md#deletemitigationactionrequestrequesttypedef).

Keyword-only arguments:

- `actionName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_ota_update"></a>

### delete_ota_update

Delete an OTA update.

Type annotations for `aiobotocore.create_client("iot").delete_ota_update`
method.

Boto3 documentation:
[IoT.Client.delete_ota_update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_ota_update)

Asynchronous method. Use `await delete_ota_update(...)` for a synchronous call.

Arguments mapping described in
[DeleteOTAUpdateRequestRequestTypeDef](./type_defs.md#deleteotaupdaterequestrequesttypedef).

Keyword-only arguments:

- `otaUpdateId`: `str` *(required)*
- `deleteStream`: `bool`
- `forceDeleteAWSJob`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_policy"></a>

### delete_policy

Deletes the specified policy.

Type annotations for `aiobotocore.create_client("iot").delete_policy` method.

Boto3 documentation:
[IoT.Client.delete_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_policy)

Asynchronous method. Use `await delete_policy(...)` for a synchronous call.

Arguments mapping described in
[DeletePolicyRequestRequestTypeDef](./type_defs.md#deletepolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*

<a id="delete_policy_version"></a>

### delete_policy_version

Deletes the specified version of the specified policy.

Type annotations for `aiobotocore.create_client("iot").delete_policy_version`
method.

Boto3 documentation:
[IoT.Client.delete_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_policy_version)

Asynchronous method. Use `await delete_policy_version(...)` for a synchronous
call.

Arguments mapping described in
[DeletePolicyVersionRequestRequestTypeDef](./type_defs.md#deletepolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `policyVersionId`: `str` *(required)*

<a id="delete_provisioning_template"></a>

### delete_provisioning_template

Deletes a fleet provisioning template.

Type annotations for
`aiobotocore.create_client("iot").delete_provisioning_template` method.

Boto3 documentation:
[IoT.Client.delete_provisioning_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_provisioning_template)

Asynchronous method. Use `await delete_provisioning_template(...)` for a
synchronous call.

Arguments mapping described in
[DeleteProvisioningTemplateRequestRequestTypeDef](./type_defs.md#deleteprovisioningtemplaterequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_provisioning_template_version"></a>

### delete_provisioning_template_version

Deletes a fleet provisioning template version.

Type annotations for
`aiobotocore.create_client("iot").delete_provisioning_template_version` method.

Boto3 documentation:
[IoT.Client.delete_provisioning_template_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_provisioning_template_version)

Asynchronous method. Use `await delete_provisioning_template_version(...)` for
a synchronous call.

Arguments mapping described in
[DeleteProvisioningTemplateVersionRequestRequestTypeDef](./type_defs.md#deleteprovisioningtemplateversionrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `versionId`: `int` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_registration_code"></a>

### delete_registration_code

Deletes a CA certificate registration code.

Type annotations for
`aiobotocore.create_client("iot").delete_registration_code` method.

Boto3 documentation:
[IoT.Client.delete_registration_code](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_registration_code)

Asynchronous method. Use `await delete_registration_code(...)` for a
synchronous call.

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_role_alias"></a>

### delete_role_alias

Deletes a role alias Requires permission to access the
\[DeleteRoleAlias\](https://docs.aws.amazon.com/service-
authorization/latest/reference/list_awsiot.html#awsiot-actions-as-permissions)\_
action.

Type annotations for `aiobotocore.create_client("iot").delete_role_alias`
method.

Boto3 documentation:
[IoT.Client.delete_role_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_role_alias)

Asynchronous method. Use `await delete_role_alias(...)` for a synchronous call.

Arguments mapping described in
[DeleteRoleAliasRequestRequestTypeDef](./type_defs.md#deleterolealiasrequestrequesttypedef).

Keyword-only arguments:

- `roleAlias`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_scheduled_audit"></a>

### delete_scheduled_audit

Deletes a scheduled audit.

Type annotations for `aiobotocore.create_client("iot").delete_scheduled_audit`
method.

Boto3 documentation:
[IoT.Client.delete_scheduled_audit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_scheduled_audit)

Asynchronous method. Use `await delete_scheduled_audit(...)` for a synchronous
call.

Arguments mapping described in
[DeleteScheduledAuditRequestRequestTypeDef](./type_defs.md#deletescheduledauditrequestrequesttypedef).

Keyword-only arguments:

- `scheduledAuditName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_security_profile"></a>

### delete_security_profile

Deletes a Device Defender security profile.

Type annotations for `aiobotocore.create_client("iot").delete_security_profile`
method.

Boto3 documentation:
[IoT.Client.delete_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_security_profile)

Asynchronous method. Use `await delete_security_profile(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSecurityProfileRequestRequestTypeDef](./type_defs.md#deletesecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_stream"></a>

### delete_stream

Deletes a stream.

Type annotations for `aiobotocore.create_client("iot").delete_stream` method.

Boto3 documentation:
[IoT.Client.delete_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_stream)

Asynchronous method. Use `await delete_stream(...)` for a synchronous call.

Arguments mapping described in
[DeleteStreamRequestRequestTypeDef](./type_defs.md#deletestreamrequestrequesttypedef).

Keyword-only arguments:

- `streamId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_thing"></a>

### delete_thing

Deletes the specified thing.

Type annotations for `aiobotocore.create_client("iot").delete_thing` method.

Boto3 documentation:
[IoT.Client.delete_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_thing)

Asynchronous method. Use `await delete_thing(...)` for a synchronous call.

Arguments mapping described in
[DeleteThingRequestRequestTypeDef](./type_defs.md#deletethingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_thing_group"></a>

### delete_thing_group

Deletes a thing group.

Type annotations for `aiobotocore.create_client("iot").delete_thing_group`
method.

Boto3 documentation:
[IoT.Client.delete_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_thing_group)

Asynchronous method. Use `await delete_thing_group(...)` for a synchronous
call.

Arguments mapping described in
[DeleteThingGroupRequestRequestTypeDef](./type_defs.md#deletethinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_thing_type"></a>

### delete_thing_type

Deletes the specified thing type.

Type annotations for `aiobotocore.create_client("iot").delete_thing_type`
method.

Boto3 documentation:
[IoT.Client.delete_thing_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_thing_type)

Asynchronous method. Use `await delete_thing_type(...)` for a synchronous call.

Arguments mapping described in
[DeleteThingTypeRequestRequestTypeDef](./type_defs.md#deletethingtyperequestrequesttypedef).

Keyword-only arguments:

- `thingTypeName`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_topic_rule"></a>

### delete_topic_rule

Deletes the rule.

Type annotations for `aiobotocore.create_client("iot").delete_topic_rule`
method.

Boto3 documentation:
[IoT.Client.delete_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_topic_rule)

Asynchronous method. Use `await delete_topic_rule(...)` for a synchronous call.

Arguments mapping described in
[DeleteTopicRuleRequestRequestTypeDef](./type_defs.md#deletetopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*

<a id="delete_topic_rule_destination"></a>

### delete_topic_rule_destination

Deletes a topic rule destination.

Type annotations for
`aiobotocore.create_client("iot").delete_topic_rule_destination` method.

Boto3 documentation:
[IoT.Client.delete_topic_rule_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_topic_rule_destination)

Asynchronous method. Use `await delete_topic_rule_destination(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTopicRuleDestinationRequestRequestTypeDef](./type_defs.md#deletetopicruledestinationrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="delete_v2_logging_level"></a>

### delete_v2_logging_level

Deletes a logging level.

Type annotations for `aiobotocore.create_client("iot").delete_v2_logging_level`
method.

Boto3 documentation:
[IoT.Client.delete_v2_logging_level](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_v2_logging_level)

Asynchronous method. Use `await delete_v2_logging_level(...)` for a synchronous
call.

Arguments mapping described in
[DeleteV2LoggingLevelRequestRequestTypeDef](./type_defs.md#deletev2logginglevelrequestrequesttypedef).

Keyword-only arguments:

- `targetType`: [LogTargetTypeType](./literals.md#logtargettypetype)
  *(required)*
- `targetName`: `str` *(required)*

<a id="deprecate_thing_type"></a>

### deprecate_thing_type

Deprecates a thing type.

Type annotations for `aiobotocore.create_client("iot").deprecate_thing_type`
method.

Boto3 documentation:
[IoT.Client.deprecate_thing_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.deprecate_thing_type)

Asynchronous method. Use `await deprecate_thing_type(...)` for a synchronous
call.

Arguments mapping described in
[DeprecateThingTypeRequestRequestTypeDef](./type_defs.md#deprecatethingtyperequestrequesttypedef).

Keyword-only arguments:

- `thingTypeName`: `str` *(required)*
- `undoDeprecate`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="describe_account_audit_configuration"></a>

### describe_account_audit_configuration

Gets information about the Device Defender audit settings for this account.

Type annotations for
`aiobotocore.create_client("iot").describe_account_audit_configuration` method.

Boto3 documentation:
[IoT.Client.describe_account_audit_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_account_audit_configuration)

Asynchronous method. Use `await describe_account_audit_configuration(...)` for
a synchronous call.

Returns a `Coroutine` for
[DescribeAccountAuditConfigurationResponseTypeDef](./type_defs.md#describeaccountauditconfigurationresponsetypedef).

<a id="describe_audit_finding"></a>

### describe_audit_finding

Gets information about a single audit finding.

Type annotations for `aiobotocore.create_client("iot").describe_audit_finding`
method.

Boto3 documentation:
[IoT.Client.describe_audit_finding](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_audit_finding)

Asynchronous method. Use `await describe_audit_finding(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAuditFindingRequestRequestTypeDef](./type_defs.md#describeauditfindingrequestrequesttypedef).

Keyword-only arguments:

- `findingId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAuditFindingResponseTypeDef](./type_defs.md#describeauditfindingresponsetypedef).

<a id="describe_audit_mitigation_actions_task"></a>

### describe_audit_mitigation_actions_task

Gets information about an audit mitigation task that is used to apply
mitigation actions to a set of audit findings.

Type annotations for
`aiobotocore.create_client("iot").describe_audit_mitigation_actions_task`
method.

Boto3 documentation:
[IoT.Client.describe_audit_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_audit_mitigation_actions_task)

Asynchronous method. Use `await describe_audit_mitigation_actions_task(...)`
for a synchronous call.

Arguments mapping described in
[DescribeAuditMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#describeauditmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAuditMitigationActionsTaskResponseTypeDef](./type_defs.md#describeauditmitigationactionstaskresponsetypedef).

<a id="describe_audit_suppression"></a>

### describe_audit_suppression

Gets information about a Device Defender audit suppression.

Type annotations for
`aiobotocore.create_client("iot").describe_audit_suppression` method.

Boto3 documentation:
[IoT.Client.describe_audit_suppression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_audit_suppression)

Asynchronous method. Use `await describe_audit_suppression(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAuditSuppressionRequestRequestTypeDef](./type_defs.md#describeauditsuppressionrequestrequesttypedef).

Keyword-only arguments:

- `checkName`: `str` *(required)*
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
  *(required)*

Returns a `Coroutine` for
[DescribeAuditSuppressionResponseTypeDef](./type_defs.md#describeauditsuppressionresponsetypedef).

<a id="describe_audit_task"></a>

### describe_audit_task

Gets information about a Device Defender audit.

Type annotations for `aiobotocore.create_client("iot").describe_audit_task`
method.

Boto3 documentation:
[IoT.Client.describe_audit_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_audit_task)

Asynchronous method. Use `await describe_audit_task(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAuditTaskRequestRequestTypeDef](./type_defs.md#describeaudittaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAuditTaskResponseTypeDef](./type_defs.md#describeaudittaskresponsetypedef).

<a id="describe_authorizer"></a>

### describe_authorizer

Describes an authorizer.

Type annotations for `aiobotocore.create_client("iot").describe_authorizer`
method.

Boto3 documentation:
[IoT.Client.describe_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_authorizer)

Asynchronous method. Use `await describe_authorizer(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAuthorizerRequestRequestTypeDef](./type_defs.md#describeauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeAuthorizerResponseTypeDef](./type_defs.md#describeauthorizerresponsetypedef).

<a id="describe_billing_group"></a>

### describe_billing_group

Returns information about a billing group.

Type annotations for `aiobotocore.create_client("iot").describe_billing_group`
method.

Boto3 documentation:
[IoT.Client.describe_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_billing_group)

Asynchronous method. Use `await describe_billing_group(...)` for a synchronous
call.

Arguments mapping described in
[DescribeBillingGroupRequestRequestTypeDef](./type_defs.md#describebillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeBillingGroupResponseTypeDef](./type_defs.md#describebillinggroupresponsetypedef).

<a id="describe_ca_certificate"></a>

### describe_ca_certificate

Describes a registered CA certificate.

Type annotations for `aiobotocore.create_client("iot").describe_ca_certificate`
method.

Boto3 documentation:
[IoT.Client.describe_ca_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_ca_certificate)

Asynchronous method. Use `await describe_ca_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCACertificateRequestRequestTypeDef](./type_defs.md#describecacertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeCACertificateResponseTypeDef](./type_defs.md#describecacertificateresponsetypedef).

<a id="describe_certificate"></a>

### describe_certificate

Gets information about the specified certificate.

Type annotations for `aiobotocore.create_client("iot").describe_certificate`
method.

Boto3 documentation:
[IoT.Client.describe_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_certificate)

Asynchronous method. Use `await describe_certificate(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCertificateRequestRequestTypeDef](./type_defs.md#describecertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeCertificateResponseTypeDef](./type_defs.md#describecertificateresponsetypedef).

<a id="describe_custom_metric"></a>

### describe_custom_metric

Gets information about a Device Defender detect custom metric.

Type annotations for `aiobotocore.create_client("iot").describe_custom_metric`
method.

Boto3 documentation:
[IoT.Client.describe_custom_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_custom_metric)

Asynchronous method. Use `await describe_custom_metric(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCustomMetricRequestRequestTypeDef](./type_defs.md#describecustommetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeCustomMetricResponseTypeDef](./type_defs.md#describecustommetricresponsetypedef).

<a id="describe_default_authorizer"></a>

### describe_default_authorizer

Describes the default authorizer.

Type annotations for
`aiobotocore.create_client("iot").describe_default_authorizer` method.

Boto3 documentation:
[IoT.Client.describe_default_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_default_authorizer)

Asynchronous method. Use `await describe_default_authorizer(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeDefaultAuthorizerResponseTypeDef](./type_defs.md#describedefaultauthorizerresponsetypedef).

<a id="describe_detect_mitigation_actions_task"></a>

### describe_detect_mitigation_actions_task

Gets information about a Device Defender ML Detect mitigation action.

Type annotations for
`aiobotocore.create_client("iot").describe_detect_mitigation_actions_task`
method.

Boto3 documentation:
[IoT.Client.describe_detect_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_detect_mitigation_actions_task)

Asynchronous method. Use `await describe_detect_mitigation_actions_task(...)`
for a synchronous call.

Arguments mapping described in
[DescribeDetectMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#describedetectmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDetectMitigationActionsTaskResponseTypeDef](./type_defs.md#describedetectmitigationactionstaskresponsetypedef).

<a id="describe_dimension"></a>

### describe_dimension

Provides details about a dimension that is defined in your Amazon Web Services
accounts.

Type annotations for `aiobotocore.create_client("iot").describe_dimension`
method.

Boto3 documentation:
[IoT.Client.describe_dimension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_dimension)

Asynchronous method. Use `await describe_dimension(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDimensionRequestRequestTypeDef](./type_defs.md#describedimensionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDimensionResponseTypeDef](./type_defs.md#describedimensionresponsetypedef).

<a id="describe_domain_configuration"></a>

### describe_domain_configuration

Gets summary information about a domain configuration.

Type annotations for
`aiobotocore.create_client("iot").describe_domain_configuration` method.

Boto3 documentation:
[IoT.Client.describe_domain_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_domain_configuration)

Asynchronous method. Use `await describe_domain_configuration(...)` for a
synchronous call.

Arguments mapping described in
[DescribeDomainConfigurationRequestRequestTypeDef](./type_defs.md#describedomainconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `domainConfigurationName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeDomainConfigurationResponseTypeDef](./type_defs.md#describedomainconfigurationresponsetypedef).

<a id="describe_endpoint"></a>

### describe_endpoint

Returns a unique endpoint specific to the Amazon Web Services account making
the call.

Type annotations for `aiobotocore.create_client("iot").describe_endpoint`
method.

Boto3 documentation:
[IoT.Client.describe_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_endpoint)

Asynchronous method. Use `await describe_endpoint(...)` for a synchronous call.

Arguments mapping described in
[DescribeEndpointRequestRequestTypeDef](./type_defs.md#describeendpointrequestrequesttypedef).

Keyword-only arguments:

- `endpointType`: `str`

Returns a `Coroutine` for
[DescribeEndpointResponseTypeDef](./type_defs.md#describeendpointresponsetypedef).

<a id="describe_event_configurations"></a>

### describe_event_configurations

Describes event configurations.

Type annotations for
`aiobotocore.create_client("iot").describe_event_configurations` method.

Boto3 documentation:
[IoT.Client.describe_event_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_event_configurations)

Asynchronous method. Use `await describe_event_configurations(...)` for a
synchronous call.

Returns a `Coroutine` for
[DescribeEventConfigurationsResponseTypeDef](./type_defs.md#describeeventconfigurationsresponsetypedef).

<a id="describe_fleet_metric"></a>

### describe_fleet_metric

Gets information about the specified fleet metric.

Type annotations for `aiobotocore.create_client("iot").describe_fleet_metric`
method.

Boto3 documentation:
[IoT.Client.describe_fleet_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_fleet_metric)

Asynchronous method. Use `await describe_fleet_metric(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFleetMetricRequestRequestTypeDef](./type_defs.md#describefleetmetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFleetMetricResponseTypeDef](./type_defs.md#describefleetmetricresponsetypedef).

<a id="describe_index"></a>

### describe_index

Describes a search index.

Type annotations for `aiobotocore.create_client("iot").describe_index` method.

Boto3 documentation:
[IoT.Client.describe_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_index)

Asynchronous method. Use `await describe_index(...)` for a synchronous call.

Arguments mapping described in
[DescribeIndexRequestRequestTypeDef](./type_defs.md#describeindexrequestrequesttypedef).

Keyword-only arguments:

- `indexName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeIndexResponseTypeDef](./type_defs.md#describeindexresponsetypedef).

<a id="describe_job"></a>

### describe_job

Describes a job.

Type annotations for `aiobotocore.create_client("iot").describe_job` method.

Boto3 documentation:
[IoT.Client.describe_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_job)

Asynchronous method. Use `await describe_job(...)` for a synchronous call.

Arguments mapping described in
[DescribeJobRequestRequestTypeDef](./type_defs.md#describejobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeJobResponseTypeDef](./type_defs.md#describejobresponsetypedef).

<a id="describe_job_execution"></a>

### describe_job_execution

Describes a job execution.

Type annotations for `aiobotocore.create_client("iot").describe_job_execution`
method.

Boto3 documentation:
[IoT.Client.describe_job_execution](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_job_execution)

Asynchronous method. Use `await describe_job_execution(...)` for a synchronous
call.

Arguments mapping described in
[DescribeJobExecutionRequestRequestTypeDef](./type_defs.md#describejobexecutionrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `thingName`: `str` *(required)*
- `executionNumber`: `int`

Returns a `Coroutine` for
[DescribeJobExecutionResponseTypeDef](./type_defs.md#describejobexecutionresponsetypedef).

<a id="describe_job_template"></a>

### describe_job_template

Returns information about a job template.

Type annotations for `aiobotocore.create_client("iot").describe_job_template`
method.

Boto3 documentation:
[IoT.Client.describe_job_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_job_template)

Asynchronous method. Use `await describe_job_template(...)` for a synchronous
call.

Arguments mapping described in
[DescribeJobTemplateRequestRequestTypeDef](./type_defs.md#describejobtemplaterequestrequesttypedef).

Keyword-only arguments:

- `jobTemplateId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeJobTemplateResponseTypeDef](./type_defs.md#describejobtemplateresponsetypedef).

<a id="describe_managed_job_template"></a>

### describe_managed_job_template

View details of a managed job template.

Type annotations for
`aiobotocore.create_client("iot").describe_managed_job_template` method.

Boto3 documentation:
[IoT.Client.describe_managed_job_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_managed_job_template)

Asynchronous method. Use `await describe_managed_job_template(...)` for a
synchronous call.

Arguments mapping described in
[DescribeManagedJobTemplateRequestRequestTypeDef](./type_defs.md#describemanagedjobtemplaterequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `templateVersion`: `str`

Returns a `Coroutine` for
[DescribeManagedJobTemplateResponseTypeDef](./type_defs.md#describemanagedjobtemplateresponsetypedef).

<a id="describe_mitigation_action"></a>

### describe_mitigation_action

Gets information about a mitigation action.

Type annotations for
`aiobotocore.create_client("iot").describe_mitigation_action` method.

Boto3 documentation:
[IoT.Client.describe_mitigation_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_mitigation_action)

Asynchronous method. Use `await describe_mitigation_action(...)` for a
synchronous call.

Arguments mapping described in
[DescribeMitigationActionRequestRequestTypeDef](./type_defs.md#describemitigationactionrequestrequesttypedef).

Keyword-only arguments:

- `actionName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeMitigationActionResponseTypeDef](./type_defs.md#describemitigationactionresponsetypedef).

<a id="describe_provisioning_template"></a>

### describe_provisioning_template

Returns information about a fleet provisioning template.

Type annotations for
`aiobotocore.create_client("iot").describe_provisioning_template` method.

Boto3 documentation:
[IoT.Client.describe_provisioning_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_provisioning_template)

Asynchronous method. Use `await describe_provisioning_template(...)` for a
synchronous call.

Arguments mapping described in
[DescribeProvisioningTemplateRequestRequestTypeDef](./type_defs.md#describeprovisioningtemplaterequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeProvisioningTemplateResponseTypeDef](./type_defs.md#describeprovisioningtemplateresponsetypedef).

<a id="describe_provisioning_template_version"></a>

### describe_provisioning_template_version

Returns information about a fleet provisioning template version.

Type annotations for
`aiobotocore.create_client("iot").describe_provisioning_template_version`
method.

Boto3 documentation:
[IoT.Client.describe_provisioning_template_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_provisioning_template_version)

Asynchronous method. Use `await describe_provisioning_template_version(...)`
for a synchronous call.

Arguments mapping described in
[DescribeProvisioningTemplateVersionRequestRequestTypeDef](./type_defs.md#describeprovisioningtemplateversionrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `versionId`: `int` *(required)*

Returns a `Coroutine` for
[DescribeProvisioningTemplateVersionResponseTypeDef](./type_defs.md#describeprovisioningtemplateversionresponsetypedef).

<a id="describe_role_alias"></a>

### describe_role_alias

Describes a role alias.

Type annotations for `aiobotocore.create_client("iot").describe_role_alias`
method.

Boto3 documentation:
[IoT.Client.describe_role_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_role_alias)

Asynchronous method. Use `await describe_role_alias(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRoleAliasRequestRequestTypeDef](./type_defs.md#describerolealiasrequestrequesttypedef).

Keyword-only arguments:

- `roleAlias`: `str` *(required)*

Returns a `Coroutine` for
[DescribeRoleAliasResponseTypeDef](./type_defs.md#describerolealiasresponsetypedef).

<a id="describe_scheduled_audit"></a>

### describe_scheduled_audit

Gets information about a scheduled audit.

Type annotations for
`aiobotocore.create_client("iot").describe_scheduled_audit` method.

Boto3 documentation:
[IoT.Client.describe_scheduled_audit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_scheduled_audit)

Asynchronous method. Use `await describe_scheduled_audit(...)` for a
synchronous call.

Arguments mapping described in
[DescribeScheduledAuditRequestRequestTypeDef](./type_defs.md#describescheduledauditrequestrequesttypedef).

Keyword-only arguments:

- `scheduledAuditName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeScheduledAuditResponseTypeDef](./type_defs.md#describescheduledauditresponsetypedef).

<a id="describe_security_profile"></a>

### describe_security_profile

Gets information about a Device Defender security profile.

Type annotations for
`aiobotocore.create_client("iot").describe_security_profile` method.

Boto3 documentation:
[IoT.Client.describe_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_security_profile)

Asynchronous method. Use `await describe_security_profile(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSecurityProfileRequestRequestTypeDef](./type_defs.md#describesecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeSecurityProfileResponseTypeDef](./type_defs.md#describesecurityprofileresponsetypedef).

<a id="describe_stream"></a>

### describe_stream

Gets information about a stream.

Type annotations for `aiobotocore.create_client("iot").describe_stream` method.

Boto3 documentation:
[IoT.Client.describe_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_stream)

Asynchronous method. Use `await describe_stream(...)` for a synchronous call.

Arguments mapping described in
[DescribeStreamRequestRequestTypeDef](./type_defs.md#describestreamrequestrequesttypedef).

Keyword-only arguments:

- `streamId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeStreamResponseTypeDef](./type_defs.md#describestreamresponsetypedef).

<a id="describe_thing"></a>

### describe_thing

Gets information about the specified thing.

Type annotations for `aiobotocore.create_client("iot").describe_thing` method.

Boto3 documentation:
[IoT.Client.describe_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_thing)

Asynchronous method. Use `await describe_thing(...)` for a synchronous call.

Arguments mapping described in
[DescribeThingRequestRequestTypeDef](./type_defs.md#describethingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeThingResponseTypeDef](./type_defs.md#describethingresponsetypedef).

<a id="describe_thing_group"></a>

### describe_thing_group

Describe a thing group.

Type annotations for `aiobotocore.create_client("iot").describe_thing_group`
method.

Boto3 documentation:
[IoT.Client.describe_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_thing_group)

Asynchronous method. Use `await describe_thing_group(...)` for a synchronous
call.

Arguments mapping described in
[DescribeThingGroupRequestRequestTypeDef](./type_defs.md#describethinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeThingGroupResponseTypeDef](./type_defs.md#describethinggroupresponsetypedef).

<a id="describe_thing_registration_task"></a>

### describe_thing_registration_task

Describes a bulk thing provisioning task.

Type annotations for
`aiobotocore.create_client("iot").describe_thing_registration_task` method.

Boto3 documentation:
[IoT.Client.describe_thing_registration_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_thing_registration_task)

Asynchronous method. Use `await describe_thing_registration_task(...)` for a
synchronous call.

Arguments mapping described in
[DescribeThingRegistrationTaskRequestRequestTypeDef](./type_defs.md#describethingregistrationtaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeThingRegistrationTaskResponseTypeDef](./type_defs.md#describethingregistrationtaskresponsetypedef).

<a id="describe_thing_type"></a>

### describe_thing_type

Gets information about the specified thing type.

Type annotations for `aiobotocore.create_client("iot").describe_thing_type`
method.

Boto3 documentation:
[IoT.Client.describe_thing_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.describe_thing_type)

Asynchronous method. Use `await describe_thing_type(...)` for a synchronous
call.

Arguments mapping described in
[DescribeThingTypeRequestRequestTypeDef](./type_defs.md#describethingtyperequestrequesttypedef).

Keyword-only arguments:

- `thingTypeName`: `str` *(required)*

Returns a `Coroutine` for
[DescribeThingTypeResponseTypeDef](./type_defs.md#describethingtyperesponsetypedef).

<a id="detach_policy"></a>

### detach_policy

Detaches a policy from the specified target.

Type annotations for `aiobotocore.create_client("iot").detach_policy` method.

Boto3 documentation:
[IoT.Client.detach_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.detach_policy)

Asynchronous method. Use `await detach_policy(...)` for a synchronous call.

Arguments mapping described in
[DetachPolicyRequestRequestTypeDef](./type_defs.md#detachpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `target`: `str` *(required)*

<a id="detach_principal_policy"></a>

### detach_principal_policy

Removes the specified policy from the specified certificate.

Type annotations for `aiobotocore.create_client("iot").detach_principal_policy`
method.

Boto3 documentation:
[IoT.Client.detach_principal_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.detach_principal_policy)

Asynchronous method. Use `await detach_principal_policy(...)` for a synchronous
call.

Arguments mapping described in
[DetachPrincipalPolicyRequestRequestTypeDef](./type_defs.md#detachprincipalpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `principal`: `str` *(required)*

<a id="detach_security_profile"></a>

### detach_security_profile

Disassociates a Device Defender security profile from a thing group or from
this account.

Type annotations for `aiobotocore.create_client("iot").detach_security_profile`
method.

Boto3 documentation:
[IoT.Client.detach_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.detach_security_profile)

Asynchronous method. Use `await detach_security_profile(...)` for a synchronous
call.

Arguments mapping described in
[DetachSecurityProfileRequestRequestTypeDef](./type_defs.md#detachsecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `securityProfileTargetArn`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="detach_thing_principal"></a>

### detach_thing_principal

Detaches the specified principal from the specified thing.

Type annotations for `aiobotocore.create_client("iot").detach_thing_principal`
method.

Boto3 documentation:
[IoT.Client.detach_thing_principal](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.detach_thing_principal)

Asynchronous method. Use `await detach_thing_principal(...)` for a synchronous
call.

Arguments mapping described in
[DetachThingPrincipalRequestRequestTypeDef](./type_defs.md#detachthingprincipalrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `principal`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="disable_topic_rule"></a>

### disable_topic_rule

Disables the rule.

Type annotations for `aiobotocore.create_client("iot").disable_topic_rule`
method.

Boto3 documentation:
[IoT.Client.disable_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.disable_topic_rule)

Asynchronous method. Use `await disable_topic_rule(...)` for a synchronous
call.

Arguments mapping described in
[DisableTopicRuleRequestRequestTypeDef](./type_defs.md#disabletopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*

<a id="enable_topic_rule"></a>

### enable_topic_rule

Enables the rule.

Type annotations for `aiobotocore.create_client("iot").enable_topic_rule`
method.

Boto3 documentation:
[IoT.Client.enable_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.enable_topic_rule)

Asynchronous method. Use `await enable_topic_rule(...)` for a synchronous call.

Arguments mapping described in
[EnableTopicRuleRequestRequestTypeDef](./type_defs.md#enabletopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("iot").generate_presigned_url`
method.

Boto3 documentation:
[IoT.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_behavior_model_training_summaries"></a>

### get_behavior_model_training_summaries

Returns a Device Defender's ML Detect Security Profile training model's status.

Type annotations for
`aiobotocore.create_client("iot").get_behavior_model_training_summaries`
method.

Boto3 documentation:
[IoT.Client.get_behavior_model_training_summaries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_behavior_model_training_summaries)

Asynchronous method. Use `await get_behavior_model_training_summaries(...)` for
a synchronous call.

Arguments mapping described in
[GetBehaviorModelTrainingSummariesRequestRequestTypeDef](./type_defs.md#getbehaviormodeltrainingsummariesrequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[GetBehaviorModelTrainingSummariesResponseTypeDef](./type_defs.md#getbehaviormodeltrainingsummariesresponsetypedef).

<a id="get_buckets_aggregation"></a>

### get_buckets_aggregation

Aggregates on indexed data with search queries pertaining to particular fields.

Type annotations for `aiobotocore.create_client("iot").get_buckets_aggregation`
method.

Boto3 documentation:
[IoT.Client.get_buckets_aggregation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_buckets_aggregation)

Asynchronous method. Use `await get_buckets_aggregation(...)` for a synchronous
call.

Arguments mapping described in
[GetBucketsAggregationRequestRequestTypeDef](./type_defs.md#getbucketsaggregationrequestrequesttypedef).

Keyword-only arguments:

- `queryString`: `str` *(required)*
- `aggregationField`: `str` *(required)*
- `bucketsAggregationType`:
  [BucketsAggregationTypeTypeDef](./type_defs.md#bucketsaggregationtypetypedef)
  *(required)*
- `indexName`: `str`
- `queryVersion`: `str`

Returns a `Coroutine` for
[GetBucketsAggregationResponseTypeDef](./type_defs.md#getbucketsaggregationresponsetypedef).

<a id="get_cardinality"></a>

### get_cardinality

Returns the approximate count of unique values that match the query.

Type annotations for `aiobotocore.create_client("iot").get_cardinality` method.

Boto3 documentation:
[IoT.Client.get_cardinality](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_cardinality)

Asynchronous method. Use `await get_cardinality(...)` for a synchronous call.

Arguments mapping described in
[GetCardinalityRequestRequestTypeDef](./type_defs.md#getcardinalityrequestrequesttypedef).

Keyword-only arguments:

- `queryString`: `str` *(required)*
- `indexName`: `str`
- `aggregationField`: `str`
- `queryVersion`: `str`

Returns a `Coroutine` for
[GetCardinalityResponseTypeDef](./type_defs.md#getcardinalityresponsetypedef).

<a id="get_effective_policies"></a>

### get_effective_policies

Gets a list of the policies that have an effect on the authorization behavior
of the specified device when it connects to the IoT device gateway.

Type annotations for `aiobotocore.create_client("iot").get_effective_policies`
method.

Boto3 documentation:
[IoT.Client.get_effective_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_effective_policies)

Asynchronous method. Use `await get_effective_policies(...)` for a synchronous
call.

Arguments mapping described in
[GetEffectivePoliciesRequestRequestTypeDef](./type_defs.md#geteffectivepoliciesrequestrequesttypedef).

Keyword-only arguments:

- `principal`: `str`
- `cognitoIdentityPoolId`: `str`
- `thingName`: `str`

Returns a `Coroutine` for
[GetEffectivePoliciesResponseTypeDef](./type_defs.md#geteffectivepoliciesresponsetypedef).

<a id="get_indexing_configuration"></a>

### get_indexing_configuration

Gets the indexing configuration.

Type annotations for
`aiobotocore.create_client("iot").get_indexing_configuration` method.

Boto3 documentation:
[IoT.Client.get_indexing_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_indexing_configuration)

Asynchronous method. Use `await get_indexing_configuration(...)` for a
synchronous call.

Returns a `Coroutine` for
[GetIndexingConfigurationResponseTypeDef](./type_defs.md#getindexingconfigurationresponsetypedef).

<a id="get_job_document"></a>

### get_job_document

Gets a job document.

Type annotations for `aiobotocore.create_client("iot").get_job_document`
method.

Boto3 documentation:
[IoT.Client.get_job_document](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_job_document)

Asynchronous method. Use `await get_job_document(...)` for a synchronous call.

Arguments mapping described in
[GetJobDocumentRequestRequestTypeDef](./type_defs.md#getjobdocumentrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*

Returns a `Coroutine` for
[GetJobDocumentResponseTypeDef](./type_defs.md#getjobdocumentresponsetypedef).

<a id="get_logging_options"></a>

### get_logging_options

Gets the logging options.

Type annotations for `aiobotocore.create_client("iot").get_logging_options`
method.

Boto3 documentation:
[IoT.Client.get_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_logging_options)

Asynchronous method. Use `await get_logging_options(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetLoggingOptionsResponseTypeDef](./type_defs.md#getloggingoptionsresponsetypedef).

<a id="get_ota_update"></a>

### get_ota_update

Gets an OTA update.

Type annotations for `aiobotocore.create_client("iot").get_ota_update` method.

Boto3 documentation:
[IoT.Client.get_ota_update](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_ota_update)

Asynchronous method. Use `await get_ota_update(...)` for a synchronous call.

Arguments mapping described in
[GetOTAUpdateRequestRequestTypeDef](./type_defs.md#getotaupdaterequestrequesttypedef).

Keyword-only arguments:

- `otaUpdateId`: `str` *(required)*

Returns a `Coroutine` for
[GetOTAUpdateResponseTypeDef](./type_defs.md#getotaupdateresponsetypedef).

<a id="get_percentiles"></a>

### get_percentiles

Groups the aggregated values that match the query into percentile groupings.

Type annotations for `aiobotocore.create_client("iot").get_percentiles` method.

Boto3 documentation:
[IoT.Client.get_percentiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_percentiles)

Asynchronous method. Use `await get_percentiles(...)` for a synchronous call.

Arguments mapping described in
[GetPercentilesRequestRequestTypeDef](./type_defs.md#getpercentilesrequestrequesttypedef).

Keyword-only arguments:

- `queryString`: `str` *(required)*
- `indexName`: `str`
- `aggregationField`: `str`
- `queryVersion`: `str`
- `percents`: `Sequence`\[`float`\]

Returns a `Coroutine` for
[GetPercentilesResponseTypeDef](./type_defs.md#getpercentilesresponsetypedef).

<a id="get_policy"></a>

### get_policy

Gets information about the specified policy with the policy document of the
default version.

Type annotations for `aiobotocore.create_client("iot").get_policy` method.

Boto3 documentation:
[IoT.Client.get_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_policy)

Asynchronous method. Use `await get_policy(...)` for a synchronous call.

Arguments mapping described in
[GetPolicyRequestRequestTypeDef](./type_defs.md#getpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*

Returns a `Coroutine` for
[GetPolicyResponseTypeDef](./type_defs.md#getpolicyresponsetypedef).

<a id="get_policy_version"></a>

### get_policy_version

Gets information about the specified policy version.

Type annotations for `aiobotocore.create_client("iot").get_policy_version`
method.

Boto3 documentation:
[IoT.Client.get_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_policy_version)

Asynchronous method. Use `await get_policy_version(...)` for a synchronous
call.

Arguments mapping described in
[GetPolicyVersionRequestRequestTypeDef](./type_defs.md#getpolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `policyVersionId`: `str` *(required)*

Returns a `Coroutine` for
[GetPolicyVersionResponseTypeDef](./type_defs.md#getpolicyversionresponsetypedef).

<a id="get_registration_code"></a>

### get_registration_code

Gets a registration code used to register a CA certificate with IoT.

Type annotations for `aiobotocore.create_client("iot").get_registration_code`
method.

Boto3 documentation:
[IoT.Client.get_registration_code](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_registration_code)

Asynchronous method. Use `await get_registration_code(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetRegistrationCodeResponseTypeDef](./type_defs.md#getregistrationcoderesponsetypedef).

<a id="get_statistics"></a>

### get_statistics

Returns the count, average, sum, minimum, maximum, sum of squares, variance,
and standard deviation for the specified aggregated field.

Type annotations for `aiobotocore.create_client("iot").get_statistics` method.

Boto3 documentation:
[IoT.Client.get_statistics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_statistics)

Asynchronous method. Use `await get_statistics(...)` for a synchronous call.

Arguments mapping described in
[GetStatisticsRequestRequestTypeDef](./type_defs.md#getstatisticsrequestrequesttypedef).

Keyword-only arguments:

- `queryString`: `str` *(required)*
- `indexName`: `str`
- `aggregationField`: `str`
- `queryVersion`: `str`

Returns a `Coroutine` for
[GetStatisticsResponseTypeDef](./type_defs.md#getstatisticsresponsetypedef).

<a id="get_topic_rule"></a>

### get_topic_rule

.

Type annotations for `aiobotocore.create_client("iot").get_topic_rule` method.

Boto3 documentation:
[IoT.Client.get_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_topic_rule)

Asynchronous method. Use `await get_topic_rule(...)` for a synchronous call.

Arguments mapping described in
[GetTopicRuleRequestRequestTypeDef](./type_defs.md#gettopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*

Returns a `Coroutine` for
[GetTopicRuleResponseTypeDef](./type_defs.md#gettopicruleresponsetypedef).

<a id="get_topic_rule_destination"></a>

### get_topic_rule_destination

Gets information about a topic rule destination.

Type annotations for
`aiobotocore.create_client("iot").get_topic_rule_destination` method.

Boto3 documentation:
[IoT.Client.get_topic_rule_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_topic_rule_destination)

Asynchronous method. Use `await get_topic_rule_destination(...)` for a
synchronous call.

Arguments mapping described in
[GetTopicRuleDestinationRequestRequestTypeDef](./type_defs.md#gettopicruledestinationrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for
[GetTopicRuleDestinationResponseTypeDef](./type_defs.md#gettopicruledestinationresponsetypedef).

<a id="get_v2_logging_options"></a>

### get_v2_logging_options

Gets the fine grained logging options.

Type annotations for `aiobotocore.create_client("iot").get_v2_logging_options`
method.

Boto3 documentation:
[IoT.Client.get_v2_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_v2_logging_options)

Asynchronous method. Use `await get_v2_logging_options(...)` for a synchronous
call.

Returns a `Coroutine` for
[GetV2LoggingOptionsResponseTypeDef](./type_defs.md#getv2loggingoptionsresponsetypedef).

<a id="list_active_violations"></a>

### list_active_violations

Lists the active violations for a given Device Defender security profile.

Type annotations for `aiobotocore.create_client("iot").list_active_violations`
method.

Boto3 documentation:
[IoT.Client.list_active_violations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_active_violations)

Asynchronous method. Use `await list_active_violations(...)` for a synchronous
call.

Arguments mapping described in
[ListActiveViolationsRequestRequestTypeDef](./type_defs.md#listactiveviolationsrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str`
- `securityProfileName`: `str`
- `behaviorCriteriaType`:
  [BehaviorCriteriaTypeType](./literals.md#behaviorcriteriatypetype)
- `listSuppressedAlerts`: `bool`
- `verificationState`:
  [VerificationStateType](./literals.md#verificationstatetype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListActiveViolationsResponseTypeDef](./type_defs.md#listactiveviolationsresponsetypedef).

<a id="list_attached_policies"></a>

### list_attached_policies

Lists the policies attached to the specified thing group.

Type annotations for `aiobotocore.create_client("iot").list_attached_policies`
method.

Boto3 documentation:
[IoT.Client.list_attached_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_attached_policies)

Asynchronous method. Use `await list_attached_policies(...)` for a synchronous
call.

Arguments mapping described in
[ListAttachedPoliciesRequestRequestTypeDef](./type_defs.md#listattachedpoliciesrequestrequesttypedef).

Keyword-only arguments:

- `target`: `str` *(required)*
- `recursive`: `bool`
- `marker`: `str`
- `pageSize`: `int`

Returns a `Coroutine` for
[ListAttachedPoliciesResponseTypeDef](./type_defs.md#listattachedpoliciesresponsetypedef).

<a id="list_audit_findings"></a>

### list_audit_findings

Lists the findings (results) of a Device Defender audit or of the audits
performed during a specified time period.

Type annotations for `aiobotocore.create_client("iot").list_audit_findings`
method.

Boto3 documentation:
[IoT.Client.list_audit_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_audit_findings)

Asynchronous method. Use `await list_audit_findings(...)` for a synchronous
call.

Arguments mapping described in
[ListAuditFindingsRequestRequestTypeDef](./type_defs.md#listauditfindingsrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str`
- `checkName`: `str`
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
- `maxResults`: `int`
- `nextToken`: `str`
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]
- `listSuppressedFindings`: `bool`

Returns a `Coroutine` for
[ListAuditFindingsResponseTypeDef](./type_defs.md#listauditfindingsresponsetypedef).

<a id="list_audit_mitigation_actions_executions"></a>

### list_audit_mitigation_actions_executions

Gets the status of audit mitigation action tasks that were executed.

Type annotations for
`aiobotocore.create_client("iot").list_audit_mitigation_actions_executions`
method.

Boto3 documentation:
[IoT.Client.list_audit_mitigation_actions_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_audit_mitigation_actions_executions)

Asynchronous method. Use `await list_audit_mitigation_actions_executions(...)`
for a synchronous call.

Arguments mapping described in
[ListAuditMitigationActionsExecutionsRequestRequestTypeDef](./type_defs.md#listauditmitigationactionsexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*
- `findingId`: `str` *(required)*
- `actionStatus`:
  [AuditMitigationActionsExecutionStatusType](./literals.md#auditmitigationactionsexecutionstatustype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListAuditMitigationActionsExecutionsResponseTypeDef](./type_defs.md#listauditmitigationactionsexecutionsresponsetypedef).

<a id="list_audit_mitigation_actions_tasks"></a>

### list_audit_mitigation_actions_tasks

Gets a list of audit mitigation action tasks that match the specified filters.

Type annotations for
`aiobotocore.create_client("iot").list_audit_mitigation_actions_tasks` method.

Boto3 documentation:
[IoT.Client.list_audit_mitigation_actions_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_audit_mitigation_actions_tasks)

Asynchronous method. Use `await list_audit_mitigation_actions_tasks(...)` for a
synchronous call.

Arguments mapping described in
[ListAuditMitigationActionsTasksRequestRequestTypeDef](./type_defs.md#listauditmitigationactionstasksrequestrequesttypedef).

Keyword-only arguments:

- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `auditTaskId`: `str`
- `findingId`: `str`
- `taskStatus`:
  [AuditMitigationActionsTaskStatusType](./literals.md#auditmitigationactionstaskstatustype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListAuditMitigationActionsTasksResponseTypeDef](./type_defs.md#listauditmitigationactionstasksresponsetypedef).

<a id="list_audit_suppressions"></a>

### list_audit_suppressions

Lists your Device Defender audit listings.

Type annotations for `aiobotocore.create_client("iot").list_audit_suppressions`
method.

Boto3 documentation:
[IoT.Client.list_audit_suppressions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_audit_suppressions)

Asynchronous method. Use `await list_audit_suppressions(...)` for a synchronous
call.

Arguments mapping described in
[ListAuditSuppressionsRequestRequestTypeDef](./type_defs.md#listauditsuppressionsrequestrequesttypedef).

Keyword-only arguments:

- `checkName`: `str`
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
- `ascendingOrder`: `bool`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListAuditSuppressionsResponseTypeDef](./type_defs.md#listauditsuppressionsresponsetypedef).

<a id="list_audit_tasks"></a>

### list_audit_tasks

Lists the Device Defender audits that have been performed during a given time
period.

Type annotations for `aiobotocore.create_client("iot").list_audit_tasks`
method.

Boto3 documentation:
[IoT.Client.list_audit_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_audit_tasks)

Asynchronous method. Use `await list_audit_tasks(...)` for a synchronous call.

Arguments mapping described in
[ListAuditTasksRequestRequestTypeDef](./type_defs.md#listaudittasksrequestrequesttypedef).

Keyword-only arguments:

- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `taskType`: [AuditTaskTypeType](./literals.md#audittasktypetype)
- `taskStatus`: [AuditTaskStatusType](./literals.md#audittaskstatustype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListAuditTasksResponseTypeDef](./type_defs.md#listaudittasksresponsetypedef).

<a id="list_authorizers"></a>

### list_authorizers

Lists the authorizers registered in your account.

Type annotations for `aiobotocore.create_client("iot").list_authorizers`
method.

Boto3 documentation:
[IoT.Client.list_authorizers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_authorizers)

Asynchronous method. Use `await list_authorizers(...)` for a synchronous call.

Arguments mapping described in
[ListAuthorizersRequestRequestTypeDef](./type_defs.md#listauthorizersrequestrequesttypedef).

Keyword-only arguments:

- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`
- `status`: [AuthorizerStatusType](./literals.md#authorizerstatustype)

Returns a `Coroutine` for
[ListAuthorizersResponseTypeDef](./type_defs.md#listauthorizersresponsetypedef).

<a id="list_billing_groups"></a>

### list_billing_groups

Lists the billing groups you have created.

Type annotations for `aiobotocore.create_client("iot").list_billing_groups`
method.

Boto3 documentation:
[IoT.Client.list_billing_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_billing_groups)

Asynchronous method. Use `await list_billing_groups(...)` for a synchronous
call.

Arguments mapping described in
[ListBillingGroupsRequestRequestTypeDef](./type_defs.md#listbillinggroupsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `namePrefixFilter`: `str`

Returns a `Coroutine` for
[ListBillingGroupsResponseTypeDef](./type_defs.md#listbillinggroupsresponsetypedef).

<a id="list_ca_certificates"></a>

### list_ca_certificates

Lists the CA certificates registered for your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("iot").list_ca_certificates`
method.

Boto3 documentation:
[IoT.Client.list_ca_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_ca_certificates)

Asynchronous method. Use `await list_ca_certificates(...)` for a synchronous
call.

Arguments mapping described in
[ListCACertificatesRequestRequestTypeDef](./type_defs.md#listcacertificatesrequestrequesttypedef).

Keyword-only arguments:

- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListCACertificatesResponseTypeDef](./type_defs.md#listcacertificatesresponsetypedef).

<a id="list_certificates"></a>

### list_certificates

Lists the certificates registered in your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("iot").list_certificates`
method.

Boto3 documentation:
[IoT.Client.list_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_certificates)

Asynchronous method. Use `await list_certificates(...)` for a synchronous call.

Arguments mapping described in
[ListCertificatesRequestRequestTypeDef](./type_defs.md#listcertificatesrequestrequesttypedef).

Keyword-only arguments:

- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListCertificatesResponseTypeDef](./type_defs.md#listcertificatesresponsetypedef).

<a id="list_certificates_by_ca"></a>

### list_certificates_by_ca

List the device certificates signed by the specified CA certificate.

Type annotations for `aiobotocore.create_client("iot").list_certificates_by_ca`
method.

Boto3 documentation:
[IoT.Client.list_certificates_by_ca](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_certificates_by_ca)

Asynchronous method. Use `await list_certificates_by_ca(...)` for a synchronous
call.

Arguments mapping described in
[ListCertificatesByCARequestRequestTypeDef](./type_defs.md#listcertificatesbycarequestrequesttypedef).

Keyword-only arguments:

- `caCertificateId`: `str` *(required)*
- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListCertificatesByCAResponseTypeDef](./type_defs.md#listcertificatesbycaresponsetypedef).

<a id="list_custom_metrics"></a>

### list_custom_metrics

Lists your Device Defender detect custom metrics.

Type annotations for `aiobotocore.create_client("iot").list_custom_metrics`
method.

Boto3 documentation:
[IoT.Client.list_custom_metrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_custom_metrics)

Asynchronous method. Use `await list_custom_metrics(...)` for a synchronous
call.

Arguments mapping described in
[ListCustomMetricsRequestRequestTypeDef](./type_defs.md#listcustommetricsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListCustomMetricsResponseTypeDef](./type_defs.md#listcustommetricsresponsetypedef).

<a id="list_detect_mitigation_actions_executions"></a>

### list_detect_mitigation_actions_executions

Lists mitigation actions executions for a Device Defender ML Detect Security
Profile.

Type annotations for
`aiobotocore.create_client("iot").list_detect_mitigation_actions_executions`
method.

Boto3 documentation:
[IoT.Client.list_detect_mitigation_actions_executions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_detect_mitigation_actions_executions)

Asynchronous method. Use `await list_detect_mitigation_actions_executions(...)`
for a synchronous call.

Arguments mapping described in
[ListDetectMitigationActionsExecutionsRequestRequestTypeDef](./type_defs.md#listdetectmitigationactionsexecutionsrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str`
- `violationId`: `str`
- `thingName`: `str`
- `startTime`: `Union`\[`datetime`, `str`\]
- `endTime`: `Union`\[`datetime`, `str`\]
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListDetectMitigationActionsExecutionsResponseTypeDef](./type_defs.md#listdetectmitigationactionsexecutionsresponsetypedef).

<a id="list_detect_mitigation_actions_tasks"></a>

### list_detect_mitigation_actions_tasks

List of Device Defender ML Detect mitigation actions tasks.

Type annotations for
`aiobotocore.create_client("iot").list_detect_mitigation_actions_tasks` method.

Boto3 documentation:
[IoT.Client.list_detect_mitigation_actions_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_detect_mitigation_actions_tasks)

Asynchronous method. Use `await list_detect_mitigation_actions_tasks(...)` for
a synchronous call.

Arguments mapping described in
[ListDetectMitigationActionsTasksRequestRequestTypeDef](./type_defs.md#listdetectmitigationactionstasksrequestrequesttypedef).

Keyword-only arguments:

- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListDetectMitigationActionsTasksResponseTypeDef](./type_defs.md#listdetectmitigationactionstasksresponsetypedef).

<a id="list_dimensions"></a>

### list_dimensions

List the set of dimensions that are defined for your Amazon Web Services
accounts.

Type annotations for `aiobotocore.create_client("iot").list_dimensions` method.

Boto3 documentation:
[IoT.Client.list_dimensions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_dimensions)

Asynchronous method. Use `await list_dimensions(...)` for a synchronous call.

Arguments mapping described in
[ListDimensionsRequestRequestTypeDef](./type_defs.md#listdimensionsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListDimensionsResponseTypeDef](./type_defs.md#listdimensionsresponsetypedef).

<a id="list_domain_configurations"></a>

### list_domain_configurations

Gets a list of domain configurations for the user.

Type annotations for
`aiobotocore.create_client("iot").list_domain_configurations` method.

Boto3 documentation:
[IoT.Client.list_domain_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_domain_configurations)

Asynchronous method. Use `await list_domain_configurations(...)` for a
synchronous call.

Arguments mapping described in
[ListDomainConfigurationsRequestRequestTypeDef](./type_defs.md#listdomainconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `marker`: `str`
- `pageSize`: `int`
- `serviceType`: [ServiceTypeType](./literals.md#servicetypetype)

Returns a `Coroutine` for
[ListDomainConfigurationsResponseTypeDef](./type_defs.md#listdomainconfigurationsresponsetypedef).

<a id="list_fleet_metrics"></a>

### list_fleet_metrics

Lists all your fleet metrics.

Type annotations for `aiobotocore.create_client("iot").list_fleet_metrics`
method.

Boto3 documentation:
[IoT.Client.list_fleet_metrics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_fleet_metrics)

Asynchronous method. Use `await list_fleet_metrics(...)` for a synchronous
call.

Arguments mapping described in
[ListFleetMetricsRequestRequestTypeDef](./type_defs.md#listfleetmetricsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListFleetMetricsResponseTypeDef](./type_defs.md#listfleetmetricsresponsetypedef).

<a id="list_indices"></a>

### list_indices

Lists the search indices.

Type annotations for `aiobotocore.create_client("iot").list_indices` method.

Boto3 documentation:
[IoT.Client.list_indices](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_indices)

Asynchronous method. Use `await list_indices(...)` for a synchronous call.

Arguments mapping described in
[ListIndicesRequestRequestTypeDef](./type_defs.md#listindicesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListIndicesResponseTypeDef](./type_defs.md#listindicesresponsetypedef).

<a id="list_job_executions_for_job"></a>

### list_job_executions_for_job

Lists the job executions for a job.

Type annotations for
`aiobotocore.create_client("iot").list_job_executions_for_job` method.

Boto3 documentation:
[IoT.Client.list_job_executions_for_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_job_executions_for_job)

Asynchronous method. Use `await list_job_executions_for_job(...)` for a
synchronous call.

Arguments mapping described in
[ListJobExecutionsForJobRequestRequestTypeDef](./type_defs.md#listjobexecutionsforjobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `status`: [JobExecutionStatusType](./literals.md#jobexecutionstatustype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListJobExecutionsForJobResponseTypeDef](./type_defs.md#listjobexecutionsforjobresponsetypedef).

<a id="list_job_executions_for_thing"></a>

### list_job_executions_for_thing

Lists the job executions for the specified thing.

Type annotations for
`aiobotocore.create_client("iot").list_job_executions_for_thing` method.

Boto3 documentation:
[IoT.Client.list_job_executions_for_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_job_executions_for_thing)

Asynchronous method. Use `await list_job_executions_for_thing(...)` for a
synchronous call.

Arguments mapping described in
[ListJobExecutionsForThingRequestRequestTypeDef](./type_defs.md#listjobexecutionsforthingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `status`: [JobExecutionStatusType](./literals.md#jobexecutionstatustype)
- `namespaceId`: `str`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListJobExecutionsForThingResponseTypeDef](./type_defs.md#listjobexecutionsforthingresponsetypedef).

<a id="list_job_templates"></a>

### list_job_templates

Returns a list of job templates.

Type annotations for `aiobotocore.create_client("iot").list_job_templates`
method.

Boto3 documentation:
[IoT.Client.list_job_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_job_templates)

Asynchronous method. Use `await list_job_templates(...)` for a synchronous
call.

Arguments mapping described in
[ListJobTemplatesRequestRequestTypeDef](./type_defs.md#listjobtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListJobTemplatesResponseTypeDef](./type_defs.md#listjobtemplatesresponsetypedef).

<a id="list_jobs"></a>

### list_jobs

Lists jobs.

Type annotations for `aiobotocore.create_client("iot").list_jobs` method.

Boto3 documentation:
[IoT.Client.list_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_jobs)

Asynchronous method. Use `await list_jobs(...)` for a synchronous call.

Arguments mapping described in
[ListJobsRequestRequestTypeDef](./type_defs.md#listjobsrequestrequesttypedef).

Keyword-only arguments:

- `status`: [JobStatusType](./literals.md#jobstatustype)
- `targetSelection`: [TargetSelectionType](./literals.md#targetselectiontype)
- `maxResults`: `int`
- `nextToken`: `str`
- `thingGroupName`: `str`
- `thingGroupId`: `str`
- `namespaceId`: `str`

Returns a `Coroutine` for
[ListJobsResponseTypeDef](./type_defs.md#listjobsresponsetypedef).

<a id="list_managed_job_templates"></a>

### list_managed_job_templates

Returns a list of managed job templates.

Type annotations for
`aiobotocore.create_client("iot").list_managed_job_templates` method.

Boto3 documentation:
[IoT.Client.list_managed_job_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_managed_job_templates)

Asynchronous method. Use `await list_managed_job_templates(...)` for a
synchronous call.

Arguments mapping described in
[ListManagedJobTemplatesRequestRequestTypeDef](./type_defs.md#listmanagedjobtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str`
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListManagedJobTemplatesResponseTypeDef](./type_defs.md#listmanagedjobtemplatesresponsetypedef).

<a id="list_mitigation_actions"></a>

### list_mitigation_actions

Gets a list of all mitigation actions that match the specified filter criteria.

Type annotations for `aiobotocore.create_client("iot").list_mitigation_actions`
method.

Boto3 documentation:
[IoT.Client.list_mitigation_actions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_mitigation_actions)

Asynchronous method. Use `await list_mitigation_actions(...)` for a synchronous
call.

Arguments mapping described in
[ListMitigationActionsRequestRequestTypeDef](./type_defs.md#listmitigationactionsrequestrequesttypedef).

Keyword-only arguments:

- `actionType`:
  [MitigationActionTypeType](./literals.md#mitigationactiontypetype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListMitigationActionsResponseTypeDef](./type_defs.md#listmitigationactionsresponsetypedef).

<a id="list_ota_updates"></a>

### list_ota_updates

Lists OTA updates.

Type annotations for `aiobotocore.create_client("iot").list_ota_updates`
method.

Boto3 documentation:
[IoT.Client.list_ota_updates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_ota_updates)

Asynchronous method. Use `await list_ota_updates(...)` for a synchronous call.

Arguments mapping described in
[ListOTAUpdatesRequestRequestTypeDef](./type_defs.md#listotaupdatesrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `otaUpdateStatus`: [OTAUpdateStatusType](./literals.md#otaupdatestatustype)

Returns a `Coroutine` for
[ListOTAUpdatesResponseTypeDef](./type_defs.md#listotaupdatesresponsetypedef).

<a id="list_outgoing_certificates"></a>

### list_outgoing_certificates

Lists certificates that are being transferred but not yet accepted.

Type annotations for
`aiobotocore.create_client("iot").list_outgoing_certificates` method.

Boto3 documentation:
[IoT.Client.list_outgoing_certificates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_outgoing_certificates)

Asynchronous method. Use `await list_outgoing_certificates(...)` for a
synchronous call.

Arguments mapping described in
[ListOutgoingCertificatesRequestRequestTypeDef](./type_defs.md#listoutgoingcertificatesrequestrequesttypedef).

Keyword-only arguments:

- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListOutgoingCertificatesResponseTypeDef](./type_defs.md#listoutgoingcertificatesresponsetypedef).

<a id="list_policies"></a>

### list_policies

Lists your policies.

Type annotations for `aiobotocore.create_client("iot").list_policies` method.

Boto3 documentation:
[IoT.Client.list_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_policies)

Asynchronous method. Use `await list_policies(...)` for a synchronous call.

Arguments mapping described in
[ListPoliciesRequestRequestTypeDef](./type_defs.md#listpoliciesrequestrequesttypedef).

Keyword-only arguments:

- `marker`: `str`
- `pageSize`: `int`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListPoliciesResponseTypeDef](./type_defs.md#listpoliciesresponsetypedef).

<a id="list_policy_principals"></a>

### list_policy_principals

Lists the principals associated with the specified policy.

Type annotations for `aiobotocore.create_client("iot").list_policy_principals`
method.

Boto3 documentation:
[IoT.Client.list_policy_principals](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_policy_principals)

Asynchronous method. Use `await list_policy_principals(...)` for a synchronous
call.

Arguments mapping described in
[ListPolicyPrincipalsRequestRequestTypeDef](./type_defs.md#listpolicyprincipalsrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `marker`: `str`
- `pageSize`: `int`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListPolicyPrincipalsResponseTypeDef](./type_defs.md#listpolicyprincipalsresponsetypedef).

<a id="list_policy_versions"></a>

### list_policy_versions

Lists the versions of the specified policy and identifies the default version.

Type annotations for `aiobotocore.create_client("iot").list_policy_versions`
method.

Boto3 documentation:
[IoT.Client.list_policy_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_policy_versions)

Asynchronous method. Use `await list_policy_versions(...)` for a synchronous
call.

Arguments mapping described in
[ListPolicyVersionsRequestRequestTypeDef](./type_defs.md#listpolicyversionsrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*

Returns a `Coroutine` for
[ListPolicyVersionsResponseTypeDef](./type_defs.md#listpolicyversionsresponsetypedef).

<a id="list_principal_policies"></a>

### list_principal_policies

Lists the policies attached to the specified principal.

Type annotations for `aiobotocore.create_client("iot").list_principal_policies`
method.

Boto3 documentation:
[IoT.Client.list_principal_policies](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_principal_policies)

Asynchronous method. Use `await list_principal_policies(...)` for a synchronous
call.

Arguments mapping described in
[ListPrincipalPoliciesRequestRequestTypeDef](./type_defs.md#listprincipalpoliciesrequestrequesttypedef).

Keyword-only arguments:

- `principal`: `str` *(required)*
- `marker`: `str`
- `pageSize`: `int`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListPrincipalPoliciesResponseTypeDef](./type_defs.md#listprincipalpoliciesresponsetypedef).

<a id="list_principal_things"></a>

### list_principal_things

Lists the things associated with the specified principal.

Type annotations for `aiobotocore.create_client("iot").list_principal_things`
method.

Boto3 documentation:
[IoT.Client.list_principal_things](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_principal_things)

Asynchronous method. Use `await list_principal_things(...)` for a synchronous
call.

Arguments mapping described in
[ListPrincipalThingsRequestRequestTypeDef](./type_defs.md#listprincipalthingsrequestrequesttypedef).

Keyword-only arguments:

- `principal`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListPrincipalThingsResponseTypeDef](./type_defs.md#listprincipalthingsresponsetypedef).

<a id="list_provisioning_template_versions"></a>

### list_provisioning_template_versions

A list of fleet provisioning template versions.

Type annotations for
`aiobotocore.create_client("iot").list_provisioning_template_versions` method.

Boto3 documentation:
[IoT.Client.list_provisioning_template_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_provisioning_template_versions)

Asynchronous method. Use `await list_provisioning_template_versions(...)` for a
synchronous call.

Arguments mapping described in
[ListProvisioningTemplateVersionsRequestRequestTypeDef](./type_defs.md#listprovisioningtemplateversionsrequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListProvisioningTemplateVersionsResponseTypeDef](./type_defs.md#listprovisioningtemplateversionsresponsetypedef).

<a id="list_provisioning_templates"></a>

### list_provisioning_templates

Lists the fleet provisioning templates in your Amazon Web Services account.

Type annotations for
`aiobotocore.create_client("iot").list_provisioning_templates` method.

Boto3 documentation:
[IoT.Client.list_provisioning_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_provisioning_templates)

Asynchronous method. Use `await list_provisioning_templates(...)` for a
synchronous call.

Arguments mapping described in
[ListProvisioningTemplatesRequestRequestTypeDef](./type_defs.md#listprovisioningtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListProvisioningTemplatesResponseTypeDef](./type_defs.md#listprovisioningtemplatesresponsetypedef).

<a id="list_role_aliases"></a>

### list_role_aliases

Lists the role aliases registered in your account.

Type annotations for `aiobotocore.create_client("iot").list_role_aliases`
method.

Boto3 documentation:
[IoT.Client.list_role_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_role_aliases)

Asynchronous method. Use `await list_role_aliases(...)` for a synchronous call.

Arguments mapping described in
[ListRoleAliasesRequestRequestTypeDef](./type_defs.md#listrolealiasesrequestrequesttypedef).

Keyword-only arguments:

- `pageSize`: `int`
- `marker`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListRoleAliasesResponseTypeDef](./type_defs.md#listrolealiasesresponsetypedef).

<a id="list_scheduled_audits"></a>

### list_scheduled_audits

Lists all of your scheduled audits.

Type annotations for `aiobotocore.create_client("iot").list_scheduled_audits`
method.

Boto3 documentation:
[IoT.Client.list_scheduled_audits](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_scheduled_audits)

Asynchronous method. Use `await list_scheduled_audits(...)` for a synchronous
call.

Arguments mapping described in
[ListScheduledAuditsRequestRequestTypeDef](./type_defs.md#listscheduledauditsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListScheduledAuditsResponseTypeDef](./type_defs.md#listscheduledauditsresponsetypedef).

<a id="list_security_profiles"></a>

### list_security_profiles

Lists the Device Defender security profiles you've created.

Type annotations for `aiobotocore.create_client("iot").list_security_profiles`
method.

Boto3 documentation:
[IoT.Client.list_security_profiles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_security_profiles)

Asynchronous method. Use `await list_security_profiles(...)` for a synchronous
call.

Arguments mapping described in
[ListSecurityProfilesRequestRequestTypeDef](./type_defs.md#listsecurityprofilesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `dimensionName`: `str`
- `metricName`: `str`

Returns a `Coroutine` for
[ListSecurityProfilesResponseTypeDef](./type_defs.md#listsecurityprofilesresponsetypedef).

<a id="list_security_profiles_for_target"></a>

### list_security_profiles_for_target

Lists the Device Defender security profiles attached to a target (thing group).

Type annotations for
`aiobotocore.create_client("iot").list_security_profiles_for_target` method.

Boto3 documentation:
[IoT.Client.list_security_profiles_for_target](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_security_profiles_for_target)

Asynchronous method. Use `await list_security_profiles_for_target(...)` for a
synchronous call.

Arguments mapping described in
[ListSecurityProfilesForTargetRequestRequestTypeDef](./type_defs.md#listsecurityprofilesfortargetrequestrequesttypedef).

Keyword-only arguments:

- `securityProfileTargetArn`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `recursive`: `bool`

Returns a `Coroutine` for
[ListSecurityProfilesForTargetResponseTypeDef](./type_defs.md#listsecurityprofilesfortargetresponsetypedef).

<a id="list_streams"></a>

### list_streams

Lists all of the streams in your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("iot").list_streams` method.

Boto3 documentation:
[IoT.Client.list_streams](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_streams)

Asynchronous method. Use `await list_streams(...)` for a synchronous call.

Arguments mapping described in
[ListStreamsRequestRequestTypeDef](./type_defs.md#liststreamsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`
- `ascendingOrder`: `bool`

Returns a `Coroutine` for
[ListStreamsResponseTypeDef](./type_defs.md#liststreamsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Lists the tags (metadata) you have assigned to the resource.

Type annotations for `aiobotocore.create_client("iot").list_tags_for_resource`
method.

Boto3 documentation:
[IoT.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="list_targets_for_policy"></a>

### list_targets_for_policy

List targets for the specified policy.

Type annotations for `aiobotocore.create_client("iot").list_targets_for_policy`
method.

Boto3 documentation:
[IoT.Client.list_targets_for_policy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_targets_for_policy)

Asynchronous method. Use `await list_targets_for_policy(...)` for a synchronous
call.

Arguments mapping described in
[ListTargetsForPolicyRequestRequestTypeDef](./type_defs.md#listtargetsforpolicyrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `marker`: `str`
- `pageSize`: `int`

Returns a `Coroutine` for
[ListTargetsForPolicyResponseTypeDef](./type_defs.md#listtargetsforpolicyresponsetypedef).

<a id="list_targets_for_security_profile"></a>

### list_targets_for_security_profile

Lists the targets (thing groups) associated with a given Device Defender
security profile.

Type annotations for
`aiobotocore.create_client("iot").list_targets_for_security_profile` method.

Boto3 documentation:
[IoT.Client.list_targets_for_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_targets_for_security_profile)

Asynchronous method. Use `await list_targets_for_security_profile(...)` for a
synchronous call.

Arguments mapping described in
[ListTargetsForSecurityProfileRequestRequestTypeDef](./type_defs.md#listtargetsforsecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListTargetsForSecurityProfileResponseTypeDef](./type_defs.md#listtargetsforsecurityprofileresponsetypedef).

<a id="list_thing_groups"></a>

### list_thing_groups

List the thing groups in your account.

Type annotations for `aiobotocore.create_client("iot").list_thing_groups`
method.

Boto3 documentation:
[IoT.Client.list_thing_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_groups)

Asynchronous method. Use `await list_thing_groups(...)` for a synchronous call.

Arguments mapping described in
[ListThingGroupsRequestRequestTypeDef](./type_defs.md#listthinggroupsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `parentGroup`: `str`
- `namePrefixFilter`: `str`
- `recursive`: `bool`

Returns a `Coroutine` for
[ListThingGroupsResponseTypeDef](./type_defs.md#listthinggroupsresponsetypedef).

<a id="list_thing_groups_for_thing"></a>

### list_thing_groups_for_thing

List the thing groups to which the specified thing belongs.

Type annotations for
`aiobotocore.create_client("iot").list_thing_groups_for_thing` method.

Boto3 documentation:
[IoT.Client.list_thing_groups_for_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_groups_for_thing)

Asynchronous method. Use `await list_thing_groups_for_thing(...)` for a
synchronous call.

Arguments mapping described in
[ListThingGroupsForThingRequestRequestTypeDef](./type_defs.md#listthinggroupsforthingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListThingGroupsForThingResponseTypeDef](./type_defs.md#listthinggroupsforthingresponsetypedef).

<a id="list_thing_principals"></a>

### list_thing_principals

Lists the principals associated with the specified thing.

Type annotations for `aiobotocore.create_client("iot").list_thing_principals`
method.

Boto3 documentation:
[IoT.Client.list_thing_principals](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_principals)

Asynchronous method. Use `await list_thing_principals(...)` for a synchronous
call.

Arguments mapping described in
[ListThingPrincipalsRequestRequestTypeDef](./type_defs.md#listthingprincipalsrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListThingPrincipalsResponseTypeDef](./type_defs.md#listthingprincipalsresponsetypedef).

<a id="list_thing_registration_task_reports"></a>

### list_thing_registration_task_reports

Information about the thing registration tasks.

Type annotations for
`aiobotocore.create_client("iot").list_thing_registration_task_reports` method.

Boto3 documentation:
[IoT.Client.list_thing_registration_task_reports](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_registration_task_reports)

Asynchronous method. Use `await list_thing_registration_task_reports(...)` for
a synchronous call.

Arguments mapping described in
[ListThingRegistrationTaskReportsRequestRequestTypeDef](./type_defs.md#listthingregistrationtaskreportsrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*
- `reportType`: [ReportTypeType](./literals.md#reporttypetype) *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListThingRegistrationTaskReportsResponseTypeDef](./type_defs.md#listthingregistrationtaskreportsresponsetypedef).

<a id="list_thing_registration_tasks"></a>

### list_thing_registration_tasks

List bulk thing provisioning tasks.

Type annotations for
`aiobotocore.create_client("iot").list_thing_registration_tasks` method.

Boto3 documentation:
[IoT.Client.list_thing_registration_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_registration_tasks)

Asynchronous method. Use `await list_thing_registration_tasks(...)` for a
synchronous call.

Arguments mapping described in
[ListThingRegistrationTasksRequestRequestTypeDef](./type_defs.md#listthingregistrationtasksrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `status`: [StatusType](./literals.md#statustype)

Returns a `Coroutine` for
[ListThingRegistrationTasksResponseTypeDef](./type_defs.md#listthingregistrationtasksresponsetypedef).

<a id="list_thing_types"></a>

### list_thing_types

Lists the existing thing types.

Type annotations for `aiobotocore.create_client("iot").list_thing_types`
method.

Boto3 documentation:
[IoT.Client.list_thing_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_thing_types)

Asynchronous method. Use `await list_thing_types(...)` for a synchronous call.

Arguments mapping described in
[ListThingTypesRequestRequestTypeDef](./type_defs.md#listthingtypesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `thingTypeName`: `str`

Returns a `Coroutine` for
[ListThingTypesResponseTypeDef](./type_defs.md#listthingtypesresponsetypedef).

<a id="list_things"></a>

### list_things

Lists your things.

Type annotations for `aiobotocore.create_client("iot").list_things` method.

Boto3 documentation:
[IoT.Client.list_things](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_things)

Asynchronous method. Use `await list_things(...)` for a synchronous call.

Arguments mapping described in
[ListThingsRequestRequestTypeDef](./type_defs.md#listthingsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `attributeName`: `str`
- `attributeValue`: `str`
- `thingTypeName`: `str`
- `usePrefixAttributeValue`: `bool`

Returns a `Coroutine` for
[ListThingsResponseTypeDef](./type_defs.md#listthingsresponsetypedef).

<a id="list_things_in_billing_group"></a>

### list_things_in_billing_group

Lists the things you have added to the given billing group.

Type annotations for
`aiobotocore.create_client("iot").list_things_in_billing_group` method.

Boto3 documentation:
[IoT.Client.list_things_in_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_things_in_billing_group)

Asynchronous method. Use `await list_things_in_billing_group(...)` for a
synchronous call.

Arguments mapping described in
[ListThingsInBillingGroupRequestRequestTypeDef](./type_defs.md#listthingsinbillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListThingsInBillingGroupResponseTypeDef](./type_defs.md#listthingsinbillinggroupresponsetypedef).

<a id="list_things_in_thing_group"></a>

### list_things_in_thing_group

Lists the things in the specified group.

Type annotations for
`aiobotocore.create_client("iot").list_things_in_thing_group` method.

Boto3 documentation:
[IoT.Client.list_things_in_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_things_in_thing_group)

Asynchronous method. Use `await list_things_in_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[ListThingsInThingGroupRequestRequestTypeDef](./type_defs.md#listthingsinthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `recursive`: `bool`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListThingsInThingGroupResponseTypeDef](./type_defs.md#listthingsinthinggroupresponsetypedef).

<a id="list_topic_rule_destinations"></a>

### list_topic_rule_destinations

Lists all the topic rule destinations in your Amazon Web Services account.

Type annotations for
`aiobotocore.create_client("iot").list_topic_rule_destinations` method.

Boto3 documentation:
[IoT.Client.list_topic_rule_destinations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_topic_rule_destinations)

Asynchronous method. Use `await list_topic_rule_destinations(...)` for a
synchronous call.

Arguments mapping described in
[ListTopicRuleDestinationsRequestRequestTypeDef](./type_defs.md#listtopicruledestinationsrequestrequesttypedef).

Keyword-only arguments:

- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[ListTopicRuleDestinationsResponseTypeDef](./type_defs.md#listtopicruledestinationsresponsetypedef).

<a id="list_topic_rules"></a>

### list_topic_rules

Lists the rules for the specific topic.

Type annotations for `aiobotocore.create_client("iot").list_topic_rules`
method.

Boto3 documentation:
[IoT.Client.list_topic_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_topic_rules)

Asynchronous method. Use `await list_topic_rules(...)` for a synchronous call.

Arguments mapping described in
[ListTopicRulesRequestRequestTypeDef](./type_defs.md#listtopicrulesrequestrequesttypedef).

Keyword-only arguments:

- `topic`: `str`
- `maxResults`: `int`
- `nextToken`: `str`
- `ruleDisabled`: `bool`

Returns a `Coroutine` for
[ListTopicRulesResponseTypeDef](./type_defs.md#listtopicrulesresponsetypedef).

<a id="list_v2_logging_levels"></a>

### list_v2_logging_levels

Lists logging levels.

Type annotations for `aiobotocore.create_client("iot").list_v2_logging_levels`
method.

Boto3 documentation:
[IoT.Client.list_v2_logging_levels](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_v2_logging_levels)

Asynchronous method. Use `await list_v2_logging_levels(...)` for a synchronous
call.

Arguments mapping described in
[ListV2LoggingLevelsRequestRequestTypeDef](./type_defs.md#listv2logginglevelsrequestrequesttypedef).

Keyword-only arguments:

- `targetType`: [LogTargetTypeType](./literals.md#logtargettypetype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListV2LoggingLevelsResponseTypeDef](./type_defs.md#listv2logginglevelsresponsetypedef).

<a id="list_violation_events"></a>

### list_violation_events

Lists the Device Defender security profile violations discovered during the
given time period.

Type annotations for `aiobotocore.create_client("iot").list_violation_events`
method.

Boto3 documentation:
[IoT.Client.list_violation_events](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_violation_events)

Asynchronous method. Use `await list_violation_events(...)` for a synchronous
call.

Arguments mapping described in
[ListViolationEventsRequestRequestTypeDef](./type_defs.md#listviolationeventsrequestrequesttypedef).

Keyword-only arguments:

- `startTime`: `Union`\[`datetime`, `str`\] *(required)*
- `endTime`: `Union`\[`datetime`, `str`\] *(required)*
- `thingName`: `str`
- `securityProfileName`: `str`
- `behaviorCriteriaType`:
  [BehaviorCriteriaTypeType](./literals.md#behaviorcriteriatypetype)
- `listSuppressedAlerts`: `bool`
- `verificationState`:
  [VerificationStateType](./literals.md#verificationstatetype)
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[ListViolationEventsResponseTypeDef](./type_defs.md#listviolationeventsresponsetypedef).

<a id="put_verification_state_on_violation"></a>

### put_verification_state_on_violation

Set a verification state and provide a description of that verification state
on a violation (detect alarm).

Type annotations for
`aiobotocore.create_client("iot").put_verification_state_on_violation` method.

Boto3 documentation:
[IoT.Client.put_verification_state_on_violation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.put_verification_state_on_violation)

Asynchronous method. Use `await put_verification_state_on_violation(...)` for a
synchronous call.

Arguments mapping described in
[PutVerificationStateOnViolationRequestRequestTypeDef](./type_defs.md#putverificationstateonviolationrequestrequesttypedef).

Keyword-only arguments:

- `violationId`: `str` *(required)*
- `verificationState`:
  [VerificationStateType](./literals.md#verificationstatetype) *(required)*
- `verificationStateDescription`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="register_ca_certificate"></a>

### register_ca_certificate

Registers a CA certificate with IoT.

Type annotations for `aiobotocore.create_client("iot").register_ca_certificate`
method.

Boto3 documentation:
[IoT.Client.register_ca_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.register_ca_certificate)

Asynchronous method. Use `await register_ca_certificate(...)` for a synchronous
call.

Arguments mapping described in
[RegisterCACertificateRequestRequestTypeDef](./type_defs.md#registercacertificaterequestrequesttypedef).

Keyword-only arguments:

- `caCertificate`: `str` *(required)*
- `verificationCertificate`: `str` *(required)*
- `setAsActive`: `bool`
- `allowAutoRegistration`: `bool`
- `registrationConfig`:
  [RegistrationConfigTypeDef](./type_defs.md#registrationconfigtypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[RegisterCACertificateResponseTypeDef](./type_defs.md#registercacertificateresponsetypedef).

<a id="register_certificate"></a>

### register_certificate

Registers a device certificate with IoT.

Type annotations for `aiobotocore.create_client("iot").register_certificate`
method.

Boto3 documentation:
[IoT.Client.register_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.register_certificate)

Asynchronous method. Use `await register_certificate(...)` for a synchronous
call.

Arguments mapping described in
[RegisterCertificateRequestRequestTypeDef](./type_defs.md#registercertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificatePem`: `str` *(required)*
- `caCertificatePem`: `str`
- `setAsActive`: `bool`
- `status`: [CertificateStatusType](./literals.md#certificatestatustype)

Returns a `Coroutine` for
[RegisterCertificateResponseTypeDef](./type_defs.md#registercertificateresponsetypedef).

<a id="register_certificate_without_ca"></a>

### register_certificate_without_ca

Register a certificate that does not have a certificate authority (CA).

Type annotations for
`aiobotocore.create_client("iot").register_certificate_without_ca` method.

Boto3 documentation:
[IoT.Client.register_certificate_without_ca](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.register_certificate_without_ca)

Asynchronous method. Use `await register_certificate_without_ca(...)` for a
synchronous call.

Arguments mapping described in
[RegisterCertificateWithoutCARequestRequestTypeDef](./type_defs.md#registercertificatewithoutcarequestrequesttypedef).

Keyword-only arguments:

- `certificatePem`: `str` *(required)*
- `status`: [CertificateStatusType](./literals.md#certificatestatustype)

Returns a `Coroutine` for
[RegisterCertificateWithoutCAResponseTypeDef](./type_defs.md#registercertificatewithoutcaresponsetypedef).

<a id="register_thing"></a>

### register_thing

Provisions a thing in the device registry.

Type annotations for `aiobotocore.create_client("iot").register_thing` method.

Boto3 documentation:
[IoT.Client.register_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.register_thing)

Asynchronous method. Use `await register_thing(...)` for a synchronous call.

Arguments mapping described in
[RegisterThingRequestRequestTypeDef](./type_defs.md#registerthingrequestrequesttypedef).

Keyword-only arguments:

- `templateBody`: `str` *(required)*
- `parameters`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for
[RegisterThingResponseTypeDef](./type_defs.md#registerthingresponsetypedef).

<a id="reject_certificate_transfer"></a>

### reject_certificate_transfer

Rejects a pending certificate transfer.

Type annotations for
`aiobotocore.create_client("iot").reject_certificate_transfer` method.

Boto3 documentation:
[IoT.Client.reject_certificate_transfer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.reject_certificate_transfer)

Asynchronous method. Use `await reject_certificate_transfer(...)` for a
synchronous call.

Arguments mapping described in
[RejectCertificateTransferRequestRequestTypeDef](./type_defs.md#rejectcertificatetransferrequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `rejectReason`: `str`

<a id="remove_thing_from_billing_group"></a>

### remove_thing_from_billing_group

Removes the given thing from the billing group.

Type annotations for
`aiobotocore.create_client("iot").remove_thing_from_billing_group` method.

Boto3 documentation:
[IoT.Client.remove_thing_from_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.remove_thing_from_billing_group)

Asynchronous method. Use `await remove_thing_from_billing_group(...)` for a
synchronous call.

Arguments mapping described in
[RemoveThingFromBillingGroupRequestRequestTypeDef](./type_defs.md#removethingfrombillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str`
- `billingGroupArn`: `str`
- `thingName`: `str`
- `thingArn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="remove_thing_from_thing_group"></a>

### remove_thing_from_thing_group

Remove the specified thing from the specified group.

Type annotations for
`aiobotocore.create_client("iot").remove_thing_from_thing_group` method.

Boto3 documentation:
[IoT.Client.remove_thing_from_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.remove_thing_from_thing_group)

Asynchronous method. Use `await remove_thing_from_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[RemoveThingFromThingGroupRequestRequestTypeDef](./type_defs.md#removethingfromthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str`
- `thingGroupArn`: `str`
- `thingName`: `str`
- `thingArn`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="replace_topic_rule"></a>

### replace_topic_rule

.

Type annotations for `aiobotocore.create_client("iot").replace_topic_rule`
method.

Boto3 documentation:
[IoT.Client.replace_topic_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.replace_topic_rule)

Asynchronous method. Use `await replace_topic_rule(...)` for a synchronous
call.

Arguments mapping described in
[ReplaceTopicRuleRequestRequestTypeDef](./type_defs.md#replacetopicrulerequestrequesttypedef).

Keyword-only arguments:

- `ruleName`: `str` *(required)*
- `topicRulePayload`:
  [TopicRulePayloadTypeDef](./type_defs.md#topicrulepayloadtypedef)
  *(required)*

<a id="search_index"></a>

### search_index

The query search index.

Type annotations for `aiobotocore.create_client("iot").search_index` method.

Boto3 documentation:
[IoT.Client.search_index](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.search_index)

Asynchronous method. Use `await search_index(...)` for a synchronous call.

Arguments mapping described in
[SearchIndexRequestRequestTypeDef](./type_defs.md#searchindexrequestrequesttypedef).

Keyword-only arguments:

- `queryString`: `str` *(required)*
- `indexName`: `str`
- `nextToken`: `str`
- `maxResults`: `int`
- `queryVersion`: `str`

Returns a `Coroutine` for
[SearchIndexResponseTypeDef](./type_defs.md#searchindexresponsetypedef).

<a id="set_default_authorizer"></a>

### set_default_authorizer

Sets the default authorizer.

Type annotations for `aiobotocore.create_client("iot").set_default_authorizer`
method.

Boto3 documentation:
[IoT.Client.set_default_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.set_default_authorizer)

Asynchronous method. Use `await set_default_authorizer(...)` for a synchronous
call.

Arguments mapping described in
[SetDefaultAuthorizerRequestRequestTypeDef](./type_defs.md#setdefaultauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*

Returns a `Coroutine` for
[SetDefaultAuthorizerResponseTypeDef](./type_defs.md#setdefaultauthorizerresponsetypedef).

<a id="set_default_policy_version"></a>

### set_default_policy_version

Sets the specified version of the specified policy as the policy's default
(operative) version.

Type annotations for
`aiobotocore.create_client("iot").set_default_policy_version` method.

Boto3 documentation:
[IoT.Client.set_default_policy_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.set_default_policy_version)

Asynchronous method. Use `await set_default_policy_version(...)` for a
synchronous call.

Arguments mapping described in
[SetDefaultPolicyVersionRequestRequestTypeDef](./type_defs.md#setdefaultpolicyversionrequestrequesttypedef).

Keyword-only arguments:

- `policyName`: `str` *(required)*
- `policyVersionId`: `str` *(required)*

<a id="set_logging_options"></a>

### set_logging_options

Sets the logging options.

Type annotations for `aiobotocore.create_client("iot").set_logging_options`
method.

Boto3 documentation:
[IoT.Client.set_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.set_logging_options)

Asynchronous method. Use `await set_logging_options(...)` for a synchronous
call.

Arguments mapping described in
[SetLoggingOptionsRequestRequestTypeDef](./type_defs.md#setloggingoptionsrequestrequesttypedef).

Keyword-only arguments:

- `loggingOptionsPayload`:
  [LoggingOptionsPayloadTypeDef](./type_defs.md#loggingoptionspayloadtypedef)
  *(required)*

<a id="set_v2_logging_level"></a>

### set_v2_logging_level

Sets the logging level.

Type annotations for `aiobotocore.create_client("iot").set_v2_logging_level`
method.

Boto3 documentation:
[IoT.Client.set_v2_logging_level](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.set_v2_logging_level)

Asynchronous method. Use `await set_v2_logging_level(...)` for a synchronous
call.

Arguments mapping described in
[SetV2LoggingLevelRequestRequestTypeDef](./type_defs.md#setv2logginglevelrequestrequesttypedef).

Keyword-only arguments:

- `logTarget`: [LogTargetTypeDef](./type_defs.md#logtargettypedef) *(required)*
- `logLevel`: [LogLevelType](./literals.md#logleveltype) *(required)*

<a id="set_v2_logging_options"></a>

### set_v2_logging_options

Sets the logging options for the V2 logging service.

Type annotations for `aiobotocore.create_client("iot").set_v2_logging_options`
method.

Boto3 documentation:
[IoT.Client.set_v2_logging_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.set_v2_logging_options)

Asynchronous method. Use `await set_v2_logging_options(...)` for a synchronous
call.

Arguments mapping described in
[SetV2LoggingOptionsRequestRequestTypeDef](./type_defs.md#setv2loggingoptionsrequestrequesttypedef).

Keyword-only arguments:

- `roleArn`: `str`
- `defaultLogLevel`: [LogLevelType](./literals.md#logleveltype)
- `disableAllLogs`: `bool`

<a id="start_audit_mitigation_actions_task"></a>

### start_audit_mitigation_actions_task

Starts a task that applies a set of mitigation actions to the specified target.

Type annotations for
`aiobotocore.create_client("iot").start_audit_mitigation_actions_task` method.

Boto3 documentation:
[IoT.Client.start_audit_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.start_audit_mitigation_actions_task)

Asynchronous method. Use `await start_audit_mitigation_actions_task(...)` for a
synchronous call.

Arguments mapping described in
[StartAuditMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#startauditmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*
- `target`:
  [AuditMitigationActionsTaskTargetTypeDef](./type_defs.md#auditmitigationactionstasktargettypedef)
  *(required)*
- `auditCheckToActionsMapping`: `Mapping`\[`str`, `Sequence`\[`str`\]\]
  *(required)*
- `clientRequestToken`: `str` *(required)*

Returns a `Coroutine` for
[StartAuditMitigationActionsTaskResponseTypeDef](./type_defs.md#startauditmitigationactionstaskresponsetypedef).

<a id="start_detect_mitigation_actions_task"></a>

### start_detect_mitigation_actions_task

Starts a Device Defender ML Detect mitigation actions task.

Type annotations for
`aiobotocore.create_client("iot").start_detect_mitigation_actions_task` method.

Boto3 documentation:
[IoT.Client.start_detect_mitigation_actions_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.start_detect_mitigation_actions_task)

Asynchronous method. Use `await start_detect_mitigation_actions_task(...)` for
a synchronous call.

Arguments mapping described in
[StartDetectMitigationActionsTaskRequestRequestTypeDef](./type_defs.md#startdetectmitigationactionstaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*
- `target`:
  [DetectMitigationActionsTaskTargetTypeDef](./type_defs.md#detectmitigationactionstasktargettypedef)
  *(required)*
- `actions`: `Sequence`\[`str`\] *(required)*
- `clientRequestToken`: `str` *(required)*
- `violationEventOccurrenceRange`:
  [ViolationEventOccurrenceRangeTypeDef](./type_defs.md#violationeventoccurrencerangetypedef)
- `includeOnlyActiveViolations`: `bool`
- `includeSuppressedAlerts`: `bool`

Returns a `Coroutine` for
[StartDetectMitigationActionsTaskResponseTypeDef](./type_defs.md#startdetectmitigationactionstaskresponsetypedef).

<a id="start_on_demand_audit_task"></a>

### start_on_demand_audit_task

Starts an on-demand Device Defender audit.

Type annotations for
`aiobotocore.create_client("iot").start_on_demand_audit_task` method.

Boto3 documentation:
[IoT.Client.start_on_demand_audit_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.start_on_demand_audit_task)

Asynchronous method. Use `await start_on_demand_audit_task(...)` for a
synchronous call.

Arguments mapping described in
[StartOnDemandAuditTaskRequestRequestTypeDef](./type_defs.md#startondemandaudittaskrequestrequesttypedef).

Keyword-only arguments:

- `targetCheckNames`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[StartOnDemandAuditTaskResponseTypeDef](./type_defs.md#startondemandaudittaskresponsetypedef).

<a id="start_thing_registration_task"></a>

### start_thing_registration_task

Creates a bulk thing provisioning task.

Type annotations for
`aiobotocore.create_client("iot").start_thing_registration_task` method.

Boto3 documentation:
[IoT.Client.start_thing_registration_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.start_thing_registration_task)

Asynchronous method. Use `await start_thing_registration_task(...)` for a
synchronous call.

Arguments mapping described in
[StartThingRegistrationTaskRequestRequestTypeDef](./type_defs.md#startthingregistrationtaskrequestrequesttypedef).

Keyword-only arguments:

- `templateBody`: `str` *(required)*
- `inputFileBucket`: `str` *(required)*
- `inputFileKey`: `str` *(required)*
- `roleArn`: `str` *(required)*

Returns a `Coroutine` for
[StartThingRegistrationTaskResponseTypeDef](./type_defs.md#startthingregistrationtaskresponsetypedef).

<a id="stop_thing_registration_task"></a>

### stop_thing_registration_task

Cancels a bulk thing provisioning task.

Type annotations for
`aiobotocore.create_client("iot").stop_thing_registration_task` method.

Boto3 documentation:
[IoT.Client.stop_thing_registration_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.stop_thing_registration_task)

Asynchronous method. Use `await stop_thing_registration_task(...)` for a
synchronous call.

Arguments mapping described in
[StopThingRegistrationTaskRequestRequestTypeDef](./type_defs.md#stopthingregistrationtaskrequestrequesttypedef).

Keyword-only arguments:

- `taskId`: `str` *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="tag_resource"></a>

### tag_resource

Adds to or modifies the tags of the given resource.

Type annotations for `aiobotocore.create_client("iot").tag_resource` method.

Boto3 documentation:
[IoT.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="test_authorization"></a>

### test_authorization

Tests if a specified principal is authorized to perform an IoT action on a
specified resource.

Type annotations for `aiobotocore.create_client("iot").test_authorization`
method.

Boto3 documentation:
[IoT.Client.test_authorization](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.test_authorization)

Asynchronous method. Use `await test_authorization(...)` for a synchronous
call.

Arguments mapping described in
[TestAuthorizationRequestRequestTypeDef](./type_defs.md#testauthorizationrequestrequesttypedef).

Keyword-only arguments:

- `authInfos`: `Sequence`\[[AuthInfoTypeDef](./type_defs.md#authinfotypedef)\]
  *(required)*
- `principal`: `str`
- `cognitoIdentityPoolId`: `str`
- `clientId`: `str`
- `policyNamesToAdd`: `Sequence`\[`str`\]
- `policyNamesToSkip`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[TestAuthorizationResponseTypeDef](./type_defs.md#testauthorizationresponsetypedef).

<a id="test_invoke_authorizer"></a>

### test_invoke_authorizer

Tests a custom authorization behavior by invoking a specified custom
authorizer.

Type annotations for `aiobotocore.create_client("iot").test_invoke_authorizer`
method.

Boto3 documentation:
[IoT.Client.test_invoke_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.test_invoke_authorizer)

Asynchronous method. Use `await test_invoke_authorizer(...)` for a synchronous
call.

Arguments mapping described in
[TestInvokeAuthorizerRequestRequestTypeDef](./type_defs.md#testinvokeauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*
- `token`: `str`
- `tokenSignature`: `str`
- `httpContext`: [HttpContextTypeDef](./type_defs.md#httpcontexttypedef)
- `mqttContext`: [MqttContextTypeDef](./type_defs.md#mqttcontexttypedef)
- `tlsContext`: [TlsContextTypeDef](./type_defs.md#tlscontexttypedef)

Returns a `Coroutine` for
[TestInvokeAuthorizerResponseTypeDef](./type_defs.md#testinvokeauthorizerresponsetypedef).

<a id="transfer_certificate"></a>

### transfer_certificate

Transfers the specified certificate to the specified Amazon Web Services
account.

Type annotations for `aiobotocore.create_client("iot").transfer_certificate`
method.

Boto3 documentation:
[IoT.Client.transfer_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.transfer_certificate)

Asynchronous method. Use `await transfer_certificate(...)` for a synchronous
call.

Arguments mapping described in
[TransferCertificateRequestRequestTypeDef](./type_defs.md#transfercertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `targetAwsAccount`: `str` *(required)*
- `transferMessage`: `str`

Returns a `Coroutine` for
[TransferCertificateResponseTypeDef](./type_defs.md#transfercertificateresponsetypedef).

<a id="untag_resource"></a>

### untag_resource

Removes the given tags (metadata) from the resource.

Type annotations for `aiobotocore.create_client("iot").untag_resource` method.

Boto3 documentation:
[IoT.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_account_audit_configuration"></a>

### update_account_audit_configuration

Configures or reconfigures the Device Defender audit settings for this account.

Type annotations for
`aiobotocore.create_client("iot").update_account_audit_configuration` method.

Boto3 documentation:
[IoT.Client.update_account_audit_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_account_audit_configuration)

Asynchronous method. Use `await update_account_audit_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateAccountAuditConfigurationRequestRequestTypeDef](./type_defs.md#updateaccountauditconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `roleArn`: `str`
- `auditNotificationTargetConfigurations`: `Mapping`\[`Literal['SNS']` (see
  [AuditNotificationTypeType](./literals.md#auditnotificationtypetype)),
  [AuditNotificationTargetTypeDef](./type_defs.md#auditnotificationtargettypedef)\]
- `auditCheckConfigurations`: `Mapping`\[`str`,
  [AuditCheckConfigurationTypeDef](./type_defs.md#auditcheckconfigurationtypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_audit_suppression"></a>

### update_audit_suppression

Updates a Device Defender audit suppression.

Type annotations for
`aiobotocore.create_client("iot").update_audit_suppression` method.

Boto3 documentation:
[IoT.Client.update_audit_suppression](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_audit_suppression)

Asynchronous method. Use `await update_audit_suppression(...)` for a
synchronous call.

Arguments mapping described in
[UpdateAuditSuppressionRequestRequestTypeDef](./type_defs.md#updateauditsuppressionrequestrequesttypedef).

Keyword-only arguments:

- `checkName`: `str` *(required)*
- `resourceIdentifier`:
  [ResourceIdentifierTypeDef](./type_defs.md#resourceidentifiertypedef)
  *(required)*
- `expirationDate`: `Union`\[`datetime`, `str`\]
- `suppressIndefinitely`: `bool`
- `description`: `str`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_authorizer"></a>

### update_authorizer

Updates an authorizer.

Type annotations for `aiobotocore.create_client("iot").update_authorizer`
method.

Boto3 documentation:
[IoT.Client.update_authorizer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_authorizer)

Asynchronous method. Use `await update_authorizer(...)` for a synchronous call.

Arguments mapping described in
[UpdateAuthorizerRequestRequestTypeDef](./type_defs.md#updateauthorizerrequestrequesttypedef).

Keyword-only arguments:

- `authorizerName`: `str` *(required)*
- `authorizerFunctionArn`: `str`
- `tokenKeyName`: `str`
- `tokenSigningPublicKeys`: `Mapping`\[`str`, `str`\]
- `status`: [AuthorizerStatusType](./literals.md#authorizerstatustype)
- `enableCachingForHttp`: `bool`

Returns a `Coroutine` for
[UpdateAuthorizerResponseTypeDef](./type_defs.md#updateauthorizerresponsetypedef).

<a id="update_billing_group"></a>

### update_billing_group

Updates information about the billing group.

Type annotations for `aiobotocore.create_client("iot").update_billing_group`
method.

Boto3 documentation:
[IoT.Client.update_billing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_billing_group)

Asynchronous method. Use `await update_billing_group(...)` for a synchronous
call.

Arguments mapping described in
[UpdateBillingGroupRequestRequestTypeDef](./type_defs.md#updatebillinggrouprequestrequesttypedef).

Keyword-only arguments:

- `billingGroupName`: `str` *(required)*
- `billingGroupProperties`:
  [BillingGroupPropertiesTypeDef](./type_defs.md#billinggrouppropertiestypedef)
  *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for
[UpdateBillingGroupResponseTypeDef](./type_defs.md#updatebillinggroupresponsetypedef).

<a id="update_ca_certificate"></a>

### update_ca_certificate

Updates a registered CA certificate.

Type annotations for `aiobotocore.create_client("iot").update_ca_certificate`
method.

Boto3 documentation:
[IoT.Client.update_ca_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_ca_certificate)

Asynchronous method. Use `await update_ca_certificate(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCACertificateRequestRequestTypeDef](./type_defs.md#updatecacertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `newStatus`: [CACertificateStatusType](./literals.md#cacertificatestatustype)
- `newAutoRegistrationStatus`:
  [AutoRegistrationStatusType](./literals.md#autoregistrationstatustype)
- `registrationConfig`:
  [RegistrationConfigTypeDef](./type_defs.md#registrationconfigtypedef)
- `removeAutoRegistration`: `bool`

<a id="update_certificate"></a>

### update_certificate

Updates the status of the specified certificate.

Type annotations for `aiobotocore.create_client("iot").update_certificate`
method.

Boto3 documentation:
[IoT.Client.update_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_certificate)

Asynchronous method. Use `await update_certificate(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCertificateRequestRequestTypeDef](./type_defs.md#updatecertificaterequestrequesttypedef).

Keyword-only arguments:

- `certificateId`: `str` *(required)*
- `newStatus`: [CertificateStatusType](./literals.md#certificatestatustype)
  *(required)*

<a id="update_custom_metric"></a>

### update_custom_metric

Updates a Device Defender detect custom metric.

Type annotations for `aiobotocore.create_client("iot").update_custom_metric`
method.

Boto3 documentation:
[IoT.Client.update_custom_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_custom_metric)

Asynchronous method. Use `await update_custom_metric(...)` for a synchronous
call.

Arguments mapping described in
[UpdateCustomMetricRequestRequestTypeDef](./type_defs.md#updatecustommetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*
- `displayName`: `str` *(required)*

Returns a `Coroutine` for
[UpdateCustomMetricResponseTypeDef](./type_defs.md#updatecustommetricresponsetypedef).

<a id="update_dimension"></a>

### update_dimension

Updates the definition for a dimension.

Type annotations for `aiobotocore.create_client("iot").update_dimension`
method.

Boto3 documentation:
[IoT.Client.update_dimension](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_dimension)

Asynchronous method. Use `await update_dimension(...)` for a synchronous call.

Arguments mapping described in
[UpdateDimensionRequestRequestTypeDef](./type_defs.md#updatedimensionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `stringValues`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[UpdateDimensionResponseTypeDef](./type_defs.md#updatedimensionresponsetypedef).

<a id="update_domain_configuration"></a>

### update_domain_configuration

Updates values stored in the domain configuration.

Type annotations for
`aiobotocore.create_client("iot").update_domain_configuration` method.

Boto3 documentation:
[IoT.Client.update_domain_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_domain_configuration)

Asynchronous method. Use `await update_domain_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDomainConfigurationRequestRequestTypeDef](./type_defs.md#updatedomainconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `domainConfigurationName`: `str` *(required)*
- `authorizerConfig`:
  [AuthorizerConfigTypeDef](./type_defs.md#authorizerconfigtypedef)
- `domainConfigurationStatus`:
  [DomainConfigurationStatusType](./literals.md#domainconfigurationstatustype)
- `removeAuthorizerConfig`: `bool`

Returns a `Coroutine` for
[UpdateDomainConfigurationResponseTypeDef](./type_defs.md#updatedomainconfigurationresponsetypedef).

<a id="update_dynamic_thing_group"></a>

### update_dynamic_thing_group

Updates a dynamic thing group.

Type annotations for
`aiobotocore.create_client("iot").update_dynamic_thing_group` method.

Boto3 documentation:
[IoT.Client.update_dynamic_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_dynamic_thing_group)

Asynchronous method. Use `await update_dynamic_thing_group(...)` for a
synchronous call.

Arguments mapping described in
[UpdateDynamicThingGroupRequestRequestTypeDef](./type_defs.md#updatedynamicthinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `thingGroupProperties`:
  [ThingGroupPropertiesTypeDef](./type_defs.md#thinggrouppropertiestypedef)
  *(required)*
- `expectedVersion`: `int`
- `indexName`: `str`
- `queryString`: `str`
- `queryVersion`: `str`

Returns a `Coroutine` for
[UpdateDynamicThingGroupResponseTypeDef](./type_defs.md#updatedynamicthinggroupresponsetypedef).

<a id="update_event_configurations"></a>

### update_event_configurations

Updates the event configurations.

Type annotations for
`aiobotocore.create_client("iot").update_event_configurations` method.

Boto3 documentation:
[IoT.Client.update_event_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_event_configurations)

Asynchronous method. Use `await update_event_configurations(...)` for a
synchronous call.

Arguments mapping described in
[UpdateEventConfigurationsRequestRequestTypeDef](./type_defs.md#updateeventconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `eventConfigurations`:
  `Mapping`\[[EventTypeType](./literals.md#eventtypetype),
  [ConfigurationTypeDef](./type_defs.md#configurationtypedef)\]

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_fleet_metric"></a>

### update_fleet_metric

Updates the data for a fleet metric.

Type annotations for `aiobotocore.create_client("iot").update_fleet_metric`
method.

Boto3 documentation:
[IoT.Client.update_fleet_metric](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_fleet_metric)

Asynchronous method. Use `await update_fleet_metric(...)` for a synchronous
call.

Arguments mapping described in
[UpdateFleetMetricRequestRequestTypeDef](./type_defs.md#updatefleetmetricrequestrequesttypedef).

Keyword-only arguments:

- `metricName`: `str` *(required)*
- `indexName`: `str` *(required)*
- `queryString`: `str`
- `aggregationType`:
  [AggregationTypeTypeDef](./type_defs.md#aggregationtypetypedef)
- `period`: `int`
- `aggregationField`: `str`
- `description`: `str`
- `queryVersion`: `str`
- `unit`: [FleetMetricUnitType](./literals.md#fleetmetricunittype)
- `expectedVersion`: `int`

<a id="update_indexing_configuration"></a>

### update_indexing_configuration

Updates the search configuration.

Type annotations for
`aiobotocore.create_client("iot").update_indexing_configuration` method.

Boto3 documentation:
[IoT.Client.update_indexing_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_indexing_configuration)

Asynchronous method. Use `await update_indexing_configuration(...)` for a
synchronous call.

Arguments mapping described in
[UpdateIndexingConfigurationRequestRequestTypeDef](./type_defs.md#updateindexingconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `thingIndexingConfiguration`:
  [ThingIndexingConfigurationTypeDef](./type_defs.md#thingindexingconfigurationtypedef)
- `thingGroupIndexingConfiguration`:
  [ThingGroupIndexingConfigurationTypeDef](./type_defs.md#thinggroupindexingconfigurationtypedef)

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_job"></a>

### update_job

Updates supported fields of the specified job.

Type annotations for `aiobotocore.create_client("iot").update_job` method.

Boto3 documentation:
[IoT.Client.update_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_job)

Asynchronous method. Use `await update_job(...)` for a synchronous call.

Arguments mapping described in
[UpdateJobRequestRequestTypeDef](./type_defs.md#updatejobrequestrequesttypedef).

Keyword-only arguments:

- `jobId`: `str` *(required)*
- `description`: `str`
- `presignedUrlConfig`:
  [PresignedUrlConfigTypeDef](./type_defs.md#presignedurlconfigtypedef)
- `jobExecutionsRolloutConfig`:
  [JobExecutionsRolloutConfigTypeDef](./type_defs.md#jobexecutionsrolloutconfigtypedef)
- `abortConfig`: [AbortConfigTypeDef](./type_defs.md#abortconfigtypedef)
- `timeoutConfig`: [TimeoutConfigTypeDef](./type_defs.md#timeoutconfigtypedef)
- `namespaceId`: `str`

<a id="update_mitigation_action"></a>

### update_mitigation_action

Updates the definition for the specified mitigation action.

Type annotations for
`aiobotocore.create_client("iot").update_mitigation_action` method.

Boto3 documentation:
[IoT.Client.update_mitigation_action](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_mitigation_action)

Asynchronous method. Use `await update_mitigation_action(...)` for a
synchronous call.

Arguments mapping described in
[UpdateMitigationActionRequestRequestTypeDef](./type_defs.md#updatemitigationactionrequestrequesttypedef).

Keyword-only arguments:

- `actionName`: `str` *(required)*
- `roleArn`: `str`
- `actionParams`:
  [MitigationActionParamsTypeDef](./type_defs.md#mitigationactionparamstypedef)

Returns a `Coroutine` for
[UpdateMitigationActionResponseTypeDef](./type_defs.md#updatemitigationactionresponsetypedef).

<a id="update_provisioning_template"></a>

### update_provisioning_template

Updates a fleet provisioning template.

Type annotations for
`aiobotocore.create_client("iot").update_provisioning_template` method.

Boto3 documentation:
[IoT.Client.update_provisioning_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_provisioning_template)

Asynchronous method. Use `await update_provisioning_template(...)` for a
synchronous call.

Arguments mapping described in
[UpdateProvisioningTemplateRequestRequestTypeDef](./type_defs.md#updateprovisioningtemplaterequestrequesttypedef).

Keyword-only arguments:

- `templateName`: `str` *(required)*
- `description`: `str`
- `enabled`: `bool`
- `defaultVersionId`: `int`
- `provisioningRoleArn`: `str`
- `preProvisioningHook`:
  [ProvisioningHookTypeDef](./type_defs.md#provisioninghooktypedef)
- `removePreProvisioningHook`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_role_alias"></a>

### update_role_alias

Updates a role alias.

Type annotations for `aiobotocore.create_client("iot").update_role_alias`
method.

Boto3 documentation:
[IoT.Client.update_role_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_role_alias)

Asynchronous method. Use `await update_role_alias(...)` for a synchronous call.

Arguments mapping described in
[UpdateRoleAliasRequestRequestTypeDef](./type_defs.md#updaterolealiasrequestrequesttypedef).

Keyword-only arguments:

- `roleAlias`: `str` *(required)*
- `roleArn`: `str`
- `credentialDurationSeconds`: `int`

Returns a `Coroutine` for
[UpdateRoleAliasResponseTypeDef](./type_defs.md#updaterolealiasresponsetypedef).

<a id="update_scheduled_audit"></a>

### update_scheduled_audit

Updates a scheduled audit, including which checks are performed and how often
the audit takes place.

Type annotations for `aiobotocore.create_client("iot").update_scheduled_audit`
method.

Boto3 documentation:
[IoT.Client.update_scheduled_audit](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_scheduled_audit)

Asynchronous method. Use `await update_scheduled_audit(...)` for a synchronous
call.

Arguments mapping described in
[UpdateScheduledAuditRequestRequestTypeDef](./type_defs.md#updatescheduledauditrequestrequesttypedef).

Keyword-only arguments:

- `scheduledAuditName`: `str` *(required)*
- `frequency`: [AuditFrequencyType](./literals.md#auditfrequencytype)
- `dayOfMonth`: `str`
- `dayOfWeek`: [DayOfWeekType](./literals.md#dayofweektype)
- `targetCheckNames`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UpdateScheduledAuditResponseTypeDef](./type_defs.md#updatescheduledauditresponsetypedef).

<a id="update_security_profile"></a>

### update_security_profile

Updates a Device Defender security profile.

Type annotations for `aiobotocore.create_client("iot").update_security_profile`
method.

Boto3 documentation:
[IoT.Client.update_security_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_security_profile)

Asynchronous method. Use `await update_security_profile(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSecurityProfileRequestRequestTypeDef](./type_defs.md#updatesecurityprofilerequestrequesttypedef).

Keyword-only arguments:

- `securityProfileName`: `str` *(required)*
- `securityProfileDescription`: `str`
- `behaviors`: `Sequence`\[[BehaviorTypeDef](./type_defs.md#behaviortypedef)\]
- `alertTargets`: `Mapping`\[`Literal['SNS']` (see
  [AlertTargetTypeType](./literals.md#alerttargettypetype)),
  [AlertTargetTypeDef](./type_defs.md#alerttargettypedef)\]
- `additionalMetricsToRetain`: `Sequence`\[`str`\]
- `additionalMetricsToRetainV2`:
  `Sequence`\[[MetricToRetainTypeDef](./type_defs.md#metrictoretaintypedef)\]
- `deleteBehaviors`: `bool`
- `deleteAlertTargets`: `bool`
- `deleteAdditionalMetricsToRetain`: `bool`
- `expectedVersion`: `int`

Returns a `Coroutine` for
[UpdateSecurityProfileResponseTypeDef](./type_defs.md#updatesecurityprofileresponsetypedef).

<a id="update_stream"></a>

### update_stream

Updates an existing stream.

Type annotations for `aiobotocore.create_client("iot").update_stream` method.

Boto3 documentation:
[IoT.Client.update_stream](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_stream)

Asynchronous method. Use `await update_stream(...)` for a synchronous call.

Arguments mapping described in
[UpdateStreamRequestRequestTypeDef](./type_defs.md#updatestreamrequestrequesttypedef).

Keyword-only arguments:

- `streamId`: `str` *(required)*
- `description`: `str`
- `files`: `Sequence`\[[StreamFileTypeDef](./type_defs.md#streamfiletypedef)\]
- `roleArn`: `str`

Returns a `Coroutine` for
[UpdateStreamResponseTypeDef](./type_defs.md#updatestreamresponsetypedef).

<a id="update_thing"></a>

### update_thing

Updates the data for a thing.

Type annotations for `aiobotocore.create_client("iot").update_thing` method.

Boto3 documentation:
[IoT.Client.update_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_thing)

Asynchronous method. Use `await update_thing(...)` for a synchronous call.

Arguments mapping described in
[UpdateThingRequestRequestTypeDef](./type_defs.md#updatethingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str` *(required)*
- `thingTypeName`: `str`
- `attributePayload`:
  [AttributePayloadTypeDef](./type_defs.md#attributepayloadtypedef)
- `expectedVersion`: `int`
- `removeThingType`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_thing_group"></a>

### update_thing_group

Update a thing group.

Type annotations for `aiobotocore.create_client("iot").update_thing_group`
method.

Boto3 documentation:
[IoT.Client.update_thing_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_thing_group)

Asynchronous method. Use `await update_thing_group(...)` for a synchronous
call.

Arguments mapping described in
[UpdateThingGroupRequestRequestTypeDef](./type_defs.md#updatethinggrouprequestrequesttypedef).

Keyword-only arguments:

- `thingGroupName`: `str` *(required)*
- `thingGroupProperties`:
  [ThingGroupPropertiesTypeDef](./type_defs.md#thinggrouppropertiestypedef)
  *(required)*
- `expectedVersion`: `int`

Returns a `Coroutine` for
[UpdateThingGroupResponseTypeDef](./type_defs.md#updatethinggroupresponsetypedef).

<a id="update_thing_groups_for_thing"></a>

### update_thing_groups_for_thing

Updates the groups to which the thing belongs.

Type annotations for
`aiobotocore.create_client("iot").update_thing_groups_for_thing` method.

Boto3 documentation:
[IoT.Client.update_thing_groups_for_thing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_thing_groups_for_thing)

Asynchronous method. Use `await update_thing_groups_for_thing(...)` for a
synchronous call.

Arguments mapping described in
[UpdateThingGroupsForThingRequestRequestTypeDef](./type_defs.md#updatethinggroupsforthingrequestrequesttypedef).

Keyword-only arguments:

- `thingName`: `str`
- `thingGroupsToAdd`: `Sequence`\[`str`\]
- `thingGroupsToRemove`: `Sequence`\[`str`\]
- `overrideDynamicGroups`: `bool`

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="update_topic_rule_destination"></a>

### update_topic_rule_destination

Updates a topic rule destination.

Type annotations for
`aiobotocore.create_client("iot").update_topic_rule_destination` method.

Boto3 documentation:
[IoT.Client.update_topic_rule_destination](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_topic_rule_destination)

Asynchronous method. Use `await update_topic_rule_destination(...)` for a
synchronous call.

Arguments mapping described in
[UpdateTopicRuleDestinationRequestRequestTypeDef](./type_defs.md#updatetopicruledestinationrequestrequesttypedef).

Keyword-only arguments:

- `arn`: `str` *(required)*
- `status`:
  [TopicRuleDestinationStatusType](./literals.md#topicruledestinationstatustype)
  *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="validate_security_profile_behaviors"></a>

### validate_security_profile_behaviors

Validates a Device Defender security profile behaviors specification.

Type annotations for
`aiobotocore.create_client("iot").validate_security_profile_behaviors` method.

Boto3 documentation:
[IoT.Client.validate_security_profile_behaviors](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.validate_security_profile_behaviors)

Asynchronous method. Use `await validate_security_profile_behaviors(...)` for a
synchronous call.

Arguments mapping described in
[ValidateSecurityProfileBehaviorsRequestRequestTypeDef](./type_defs.md#validatesecurityprofilebehaviorsrequestrequesttypedef).

Keyword-only arguments:

- `behaviors`: `Sequence`\[[BehaviorTypeDef](./type_defs.md#behaviortypedef)\]
  *(required)*

Returns a `Coroutine` for
[ValidateSecurityProfileBehaviorsResponseTypeDef](./type_defs.md#validatesecurityprofilebehaviorsresponsetypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("iot").get_paginator` method
with overloads.

- `client.get_paginator("get_behavior_model_training_summaries")` ->
  [GetBehaviorModelTrainingSummariesPaginator](./paginators.md#getbehaviormodeltrainingsummariespaginator)
- `client.get_paginator("list_active_violations")` ->
  [ListActiveViolationsPaginator](./paginators.md#listactiveviolationspaginator)
- `client.get_paginator("list_attached_policies")` ->
  [ListAttachedPoliciesPaginator](./paginators.md#listattachedpoliciespaginator)
- `client.get_paginator("list_audit_findings")` ->
  [ListAuditFindingsPaginator](./paginators.md#listauditfindingspaginator)
- `client.get_paginator("list_audit_mitigation_actions_executions")` ->
  [ListAuditMitigationActionsExecutionsPaginator](./paginators.md#listauditmitigationactionsexecutionspaginator)
- `client.get_paginator("list_audit_mitigation_actions_tasks")` ->
  [ListAuditMitigationActionsTasksPaginator](./paginators.md#listauditmitigationactionstaskspaginator)
- `client.get_paginator("list_audit_suppressions")` ->
  [ListAuditSuppressionsPaginator](./paginators.md#listauditsuppressionspaginator)
- `client.get_paginator("list_audit_tasks")` ->
  [ListAuditTasksPaginator](./paginators.md#listaudittaskspaginator)
- `client.get_paginator("list_authorizers")` ->
  [ListAuthorizersPaginator](./paginators.md#listauthorizerspaginator)
- `client.get_paginator("list_billing_groups")` ->
  [ListBillingGroupsPaginator](./paginators.md#listbillinggroupspaginator)
- `client.get_paginator("list_ca_certificates")` ->
  [ListCACertificatesPaginator](./paginators.md#listcacertificatespaginator)
- `client.get_paginator("list_certificates")` ->
  [ListCertificatesPaginator](./paginators.md#listcertificatespaginator)
- `client.get_paginator("list_certificates_by_ca")` ->
  [ListCertificatesByCAPaginator](./paginators.md#listcertificatesbycapaginator)
- `client.get_paginator("list_custom_metrics")` ->
  [ListCustomMetricsPaginator](./paginators.md#listcustommetricspaginator)
- `client.get_paginator("list_detect_mitigation_actions_executions")` ->
  [ListDetectMitigationActionsExecutionsPaginator](./paginators.md#listdetectmitigationactionsexecutionspaginator)
- `client.get_paginator("list_detect_mitigation_actions_tasks")` ->
  [ListDetectMitigationActionsTasksPaginator](./paginators.md#listdetectmitigationactionstaskspaginator)
- `client.get_paginator("list_dimensions")` ->
  [ListDimensionsPaginator](./paginators.md#listdimensionspaginator)
- `client.get_paginator("list_domain_configurations")` ->
  [ListDomainConfigurationsPaginator](./paginators.md#listdomainconfigurationspaginator)
- `client.get_paginator("list_fleet_metrics")` ->
  [ListFleetMetricsPaginator](./paginators.md#listfleetmetricspaginator)
- `client.get_paginator("list_indices")` ->
  [ListIndicesPaginator](./paginators.md#listindicespaginator)
- `client.get_paginator("list_job_executions_for_job")` ->
  [ListJobExecutionsForJobPaginator](./paginators.md#listjobexecutionsforjobpaginator)
- `client.get_paginator("list_job_executions_for_thing")` ->
  [ListJobExecutionsForThingPaginator](./paginators.md#listjobexecutionsforthingpaginator)
- `client.get_paginator("list_job_templates")` ->
  [ListJobTemplatesPaginator](./paginators.md#listjobtemplatespaginator)
- `client.get_paginator("list_jobs")` ->
  [ListJobsPaginator](./paginators.md#listjobspaginator)
- `client.get_paginator("list_mitigation_actions")` ->
  [ListMitigationActionsPaginator](./paginators.md#listmitigationactionspaginator)
- `client.get_paginator("list_ota_updates")` ->
  [ListOTAUpdatesPaginator](./paginators.md#listotaupdatespaginator)
- `client.get_paginator("list_outgoing_certificates")` ->
  [ListOutgoingCertificatesPaginator](./paginators.md#listoutgoingcertificatespaginator)
- `client.get_paginator("list_policies")` ->
  [ListPoliciesPaginator](./paginators.md#listpoliciespaginator)
- `client.get_paginator("list_policy_principals")` ->
  [ListPolicyPrincipalsPaginator](./paginators.md#listpolicyprincipalspaginator)
- `client.get_paginator("list_principal_policies")` ->
  [ListPrincipalPoliciesPaginator](./paginators.md#listprincipalpoliciespaginator)
- `client.get_paginator("list_principal_things")` ->
  [ListPrincipalThingsPaginator](./paginators.md#listprincipalthingspaginator)
- `client.get_paginator("list_provisioning_template_versions")` ->
  [ListProvisioningTemplateVersionsPaginator](./paginators.md#listprovisioningtemplateversionspaginator)
- `client.get_paginator("list_provisioning_templates")` ->
  [ListProvisioningTemplatesPaginator](./paginators.md#listprovisioningtemplatespaginator)
- `client.get_paginator("list_role_aliases")` ->
  [ListRoleAliasesPaginator](./paginators.md#listrolealiasespaginator)
- `client.get_paginator("list_scheduled_audits")` ->
  [ListScheduledAuditsPaginator](./paginators.md#listscheduledauditspaginator)
- `client.get_paginator("list_security_profiles")` ->
  [ListSecurityProfilesPaginator](./paginators.md#listsecurityprofilespaginator)
- `client.get_paginator("list_security_profiles_for_target")` ->
  [ListSecurityProfilesForTargetPaginator](./paginators.md#listsecurityprofilesfortargetpaginator)
- `client.get_paginator("list_streams")` ->
  [ListStreamsPaginator](./paginators.md#liststreamspaginator)
- `client.get_paginator("list_tags_for_resource")` ->
  [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- `client.get_paginator("list_targets_for_policy")` ->
  [ListTargetsForPolicyPaginator](./paginators.md#listtargetsforpolicypaginator)
- `client.get_paginator("list_targets_for_security_profile")` ->
  [ListTargetsForSecurityProfilePaginator](./paginators.md#listtargetsforsecurityprofilepaginator)
- `client.get_paginator("list_thing_groups")` ->
  [ListThingGroupsPaginator](./paginators.md#listthinggroupspaginator)
- `client.get_paginator("list_thing_groups_for_thing")` ->
  [ListThingGroupsForThingPaginator](./paginators.md#listthinggroupsforthingpaginator)
- `client.get_paginator("list_thing_principals")` ->
  [ListThingPrincipalsPaginator](./paginators.md#listthingprincipalspaginator)
- `client.get_paginator("list_thing_registration_task_reports")` ->
  [ListThingRegistrationTaskReportsPaginator](./paginators.md#listthingregistrationtaskreportspaginator)
- `client.get_paginator("list_thing_registration_tasks")` ->
  [ListThingRegistrationTasksPaginator](./paginators.md#listthingregistrationtaskspaginator)
- `client.get_paginator("list_thing_types")` ->
  [ListThingTypesPaginator](./paginators.md#listthingtypespaginator)
- `client.get_paginator("list_things")` ->
  [ListThingsPaginator](./paginators.md#listthingspaginator)
- `client.get_paginator("list_things_in_billing_group")` ->
  [ListThingsInBillingGroupPaginator](./paginators.md#listthingsinbillinggrouppaginator)
- `client.get_paginator("list_things_in_thing_group")` ->
  [ListThingsInThingGroupPaginator](./paginators.md#listthingsinthinggrouppaginator)
- `client.get_paginator("list_topic_rule_destinations")` ->
  [ListTopicRuleDestinationsPaginator](./paginators.md#listtopicruledestinationspaginator)
- `client.get_paginator("list_topic_rules")` ->
  [ListTopicRulesPaginator](./paginators.md#listtopicrulespaginator)
- `client.get_paginator("list_v2_logging_levels")` ->
  [ListV2LoggingLevelsPaginator](./paginators.md#listv2logginglevelspaginator)
- `client.get_paginator("list_violation_events")` ->
  [ListViolationEventsPaginator](./paginators.md#listviolationeventspaginator)
