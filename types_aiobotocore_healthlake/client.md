<a id="healthlakeclient-for-aiobotocore-healthlake-module"></a>

# HealthLakeClient for aiobotocore HealthLake module

> [Index](..) > [HealthLake](.) > HealthLakeClient

Auto-generated documentation for
[HealthLake](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake)
type annotations stubs module
[types-aiobotocore-healthlake](https://pypi.org/project/types-aiobotocore-healthlake/).

- [HealthLakeClient for aiobotocore HealthLake module](#healthlakeclient-for-aiobotocore-healthlake-module)
  - [HealthLakeClient](#healthlakeclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_fhir_datastore](#create_fhir_datastore)
    - [delete_fhir_datastore](#delete_fhir_datastore)
    - [describe_fhir_datastore](#describe_fhir_datastore)
    - [describe_fhir_export_job](#describe_fhir_export_job)
    - [describe_fhir_import_job](#describe_fhir_import_job)
    - [generate_presigned_url](#generate_presigned_url)
    - [list_fhir_datastores](#list_fhir_datastores)
    - [list_fhir_export_jobs](#list_fhir_export_jobs)
    - [list_fhir_import_jobs](#list_fhir_import_jobs)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [start_fhir_export_job](#start_fhir_export_job)
    - [start_fhir_import_job](#start_fhir_import_job)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)

<a id="healthlakeclient"></a>

## HealthLakeClient

Type annotations for `aiobotocore.create_client("healthlake")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_healthlake.client import HealthLakeClient

def get_healthlake_client() -> HealthLakeClient:
    return Session().client("healthlake")
```

Boto3 documentation:
[HealthLake.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_healthlake.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalServerException`
- `Exceptions.ResourceNotFoundException`
- `Exceptions.ThrottlingException`
- `Exceptions.ValidationException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

HealthLakeClient exceptions.

Type annotations for `aiobotocore.create_client("healthlake").exceptions`
method.

Boto3 documentation:
[HealthLake.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("healthlake").can_paginate`
method.

Boto3 documentation:
[HealthLake.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="create_fhir_datastore"></a>

### create_fhir_datastore

Creates a Data Store that can ingest and export FHIR formatted data.

Type annotations for
`aiobotocore.create_client("healthlake").create_fhir_datastore` method.

Boto3 documentation:
[HealthLake.Client.create_fhir_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.create_fhir_datastore)

Asynchronous method. Use `await create_fhir_datastore(...)` for a synchronous
call.

Arguments mapping described in
[CreateFHIRDatastoreRequestRequestTypeDef](./type_defs.md#createfhirdatastorerequestrequesttypedef).

Keyword-only arguments:

- `DatastoreTypeVersion`: `Literal['R4']` (see
  [FHIRVersionType](./literals.md#fhirversiontype)) *(required)*
- `DatastoreName`: `str`
- `SseConfiguration`:
  [SseConfigurationTypeDef](./type_defs.md#sseconfigurationtypedef)
- `PreloadDataConfig`:
  [PreloadDataConfigTypeDef](./type_defs.md#preloaddataconfigtypedef)
- `ClientToken`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[CreateFHIRDatastoreResponseTypeDef](./type_defs.md#createfhirdatastoreresponsetypedef).

<a id="delete_fhir_datastore"></a>

### delete_fhir_datastore

Deletes a Data Store.

Type annotations for
`aiobotocore.create_client("healthlake").delete_fhir_datastore` method.

Boto3 documentation:
[HealthLake.Client.delete_fhir_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.delete_fhir_datastore)

Asynchronous method. Use `await delete_fhir_datastore(...)` for a synchronous
call.

Arguments mapping described in
[DeleteFHIRDatastoreRequestRequestTypeDef](./type_defs.md#deletefhirdatastorerequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str`

Returns a `Coroutine` for
[DeleteFHIRDatastoreResponseTypeDef](./type_defs.md#deletefhirdatastoreresponsetypedef).

<a id="describe_fhir_datastore"></a>

### describe_fhir_datastore

Gets the properties associated with the FHIR Data Store, including the Data
Store ID, Data Store ARN, Data Store name, Data Store status, created at, Data
Store type version, and Data Store endpoint.

Type annotations for
`aiobotocore.create_client("healthlake").describe_fhir_datastore` method.

Boto3 documentation:
[HealthLake.Client.describe_fhir_datastore](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.describe_fhir_datastore)

Asynchronous method. Use `await describe_fhir_datastore(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFHIRDatastoreRequestRequestTypeDef](./type_defs.md#describefhirdatastorerequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str`

Returns a `Coroutine` for
[DescribeFHIRDatastoreResponseTypeDef](./type_defs.md#describefhirdatastoreresponsetypedef).

<a id="describe_fhir_export_job"></a>

### describe_fhir_export_job

Displays the properties of a FHIR export job, including the ID, ARN, name, and
the status of the job.

Type annotations for
`aiobotocore.create_client("healthlake").describe_fhir_export_job` method.

Boto3 documentation:
[HealthLake.Client.describe_fhir_export_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.describe_fhir_export_job)

Asynchronous method. Use `await describe_fhir_export_job(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFHIRExportJobRequestRequestTypeDef](./type_defs.md#describefhirexportjobrequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str` *(required)*
- `JobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFHIRExportJobResponseTypeDef](./type_defs.md#describefhirexportjobresponsetypedef).

<a id="describe_fhir_import_job"></a>

### describe_fhir_import_job

Displays the properties of a FHIR import job, including the ID, ARN, name, and
the status of the job.

Type annotations for
`aiobotocore.create_client("healthlake").describe_fhir_import_job` method.

Boto3 documentation:
[HealthLake.Client.describe_fhir_import_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.describe_fhir_import_job)

Asynchronous method. Use `await describe_fhir_import_job(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFHIRImportJobRequestRequestTypeDef](./type_defs.md#describefhirimportjobrequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str` *(required)*
- `JobId`: `str` *(required)*

Returns a `Coroutine` for
[DescribeFHIRImportJobResponseTypeDef](./type_defs.md#describefhirimportjobresponsetypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`aiobotocore.create_client("healthlake").generate_presigned_url` method.

Boto3 documentation:
[HealthLake.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="list_fhir_datastores"></a>

### list_fhir_datastores

Lists all FHIR Data Stores that are in the user’s account, regardless of Data
Store status.

Type annotations for
`aiobotocore.create_client("healthlake").list_fhir_datastores` method.

Boto3 documentation:
[HealthLake.Client.list_fhir_datastores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.list_fhir_datastores)

Asynchronous method. Use `await list_fhir_datastores(...)` for a synchronous
call.

Arguments mapping described in
[ListFHIRDatastoresRequestRequestTypeDef](./type_defs.md#listfhirdatastoresrequestrequesttypedef).

Keyword-only arguments:

- `Filter`: [DatastoreFilterTypeDef](./type_defs.md#datastorefiltertypedef)
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[ListFHIRDatastoresResponseTypeDef](./type_defs.md#listfhirdatastoresresponsetypedef).

<a id="list_fhir_export_jobs"></a>

### list_fhir_export_jobs

Lists all FHIR export jobs associated with an account and their statuses.

Type annotations for
`aiobotocore.create_client("healthlake").list_fhir_export_jobs` method.

Boto3 documentation:
[HealthLake.Client.list_fhir_export_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.list_fhir_export_jobs)

Asynchronous method. Use `await list_fhir_export_jobs(...)` for a synchronous
call.

Arguments mapping described in
[ListFHIRExportJobsRequestRequestTypeDef](./type_defs.md#listfhirexportjobsrequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `JobName`: `str`
- `JobStatus`: [JobStatusType](./literals.md#jobstatustype)
- `SubmittedBefore`: `Union`\[`datetime`, `str`\]
- `SubmittedAfter`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[ListFHIRExportJobsResponseTypeDef](./type_defs.md#listfhirexportjobsresponsetypedef).

<a id="list_fhir_import_jobs"></a>

### list_fhir_import_jobs

Lists all FHIR import jobs associated with an account and their statuses.

Type annotations for
`aiobotocore.create_client("healthlake").list_fhir_import_jobs` method.

Boto3 documentation:
[HealthLake.Client.list_fhir_import_jobs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.list_fhir_import_jobs)

Asynchronous method. Use `await list_fhir_import_jobs(...)` for a synchronous
call.

Arguments mapping described in
[ListFHIRImportJobsRequestRequestTypeDef](./type_defs.md#listfhirimportjobsrequestrequesttypedef).

Keyword-only arguments:

- `DatastoreId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `JobName`: `str`
- `JobStatus`: [JobStatusType](./literals.md#jobstatustype)
- `SubmittedBefore`: `Union`\[`datetime`, `str`\]
- `SubmittedAfter`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[ListFHIRImportJobsResponseTypeDef](./type_defs.md#listfhirimportjobsresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Returns a list of all existing tags associated with a Data Store.

Type annotations for
`aiobotocore.create_client("healthlake").list_tags_for_resource` method.

Boto3 documentation:
[HealthLake.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="start_fhir_export_job"></a>

### start_fhir_export_job

Begins a FHIR export job.

Type annotations for
`aiobotocore.create_client("healthlake").start_fhir_export_job` method.

Boto3 documentation:
[HealthLake.Client.start_fhir_export_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.start_fhir_export_job)

Asynchronous method. Use `await start_fhir_export_job(...)` for a synchronous
call.

Arguments mapping described in
[StartFHIRExportJobRequestRequestTypeDef](./type_defs.md#startfhirexportjobrequestrequesttypedef).

Keyword-only arguments:

- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
  *(required)*
- `DatastoreId`: `str` *(required)*
- `DataAccessRoleArn`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `JobName`: `str`

Returns a `Coroutine` for
[StartFHIRExportJobResponseTypeDef](./type_defs.md#startfhirexportjobresponsetypedef).

<a id="start_fhir_import_job"></a>

### start_fhir_import_job

Begins a FHIR Import job.

Type annotations for
`aiobotocore.create_client("healthlake").start_fhir_import_job` method.

Boto3 documentation:
[HealthLake.Client.start_fhir_import_job](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.start_fhir_import_job)

Asynchronous method. Use `await start_fhir_import_job(...)` for a synchronous
call.

Arguments mapping described in
[StartFHIRImportJobRequestRequestTypeDef](./type_defs.md#startfhirimportjobrequestrequesttypedef).

Keyword-only arguments:

- `InputDataConfig`:
  [InputDataConfigTypeDef](./type_defs.md#inputdataconfigtypedef) *(required)*
- `JobOutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
  *(required)*
- `DatastoreId`: `str` *(required)*
- `DataAccessRoleArn`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `JobName`: `str`

Returns a `Coroutine` for
[StartFHIRImportJobResponseTypeDef](./type_defs.md#startfhirimportjobresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds a user specifed key and value tag to a Data Store.

Type annotations for `aiobotocore.create_client("healthlake").tag_resource`
method.

Boto3 documentation:
[HealthLake.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from a Data Store.

Type annotations for `aiobotocore.create_client("healthlake").untag_resource`
method.

Boto3 documentation:
[HealthLake.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/healthlake.html#HealthLake.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `ResourceARN`: `str` *(required)*
- `TagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].
