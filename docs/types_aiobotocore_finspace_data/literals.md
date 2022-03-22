<a id="literals-for-aiobotocore-finspacedata-module"></a>

# Literals for aiobotocore FinSpaceData module

> [Index](../README.md) > [FinSpaceData](./README.md) > Literals

Auto-generated documentation for
[FinSpaceData](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
type annotations stubs module
[types-aiobotocore-finspace-data](https://pypi.org/project/types-aiobotocore-finspace-data/).

- [Literals for aiobotocore FinSpaceData module](#literals-for-aiobotocore-finspacedata-module)
  - [ApiAccessType](#apiaccesstype)
  - [ApplicationPermissionType](#applicationpermissiontype)
  - [ChangeTypeType](#changetypetype)
  - [ColumnDataTypeType](#columndatatypetype)
  - [DataViewStatusType](#dataviewstatustype)
  - [DatasetKindType](#datasetkindtype)
  - [DatasetStatusType](#datasetstatustype)
  - [ErrorCategoryType](#errorcategorytype)
  - [ExportFileFormatType](#exportfileformattype)
  - [IngestionStatusType](#ingestionstatustype)
  - [ListChangesetsPaginatorName](#listchangesetspaginatorname)
  - [ListDataViewsPaginatorName](#listdataviewspaginatorname)
  - [ListDatasetsPaginatorName](#listdatasetspaginatorname)
  - [ListPermissionGroupsPaginatorName](#listpermissiongroupspaginatorname)
  - [ListUsersPaginatorName](#listuserspaginatorname)
  - [UserStatusType](#userstatustype)
  - [UserTypeType](#usertypetype)
  - [locationTypeType](#locationtypetype)
  - [FinSpaceDataServiceName](#finspacedataservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="apiaccesstype"></a>

## ApiAccessType

```python
from types_aiobotocore_finspace_data.literals import ApiAccessType
```

Values:

- `DISABLED`
- `ENABLED`

<a id="applicationpermissiontype"></a>

## ApplicationPermissionType

```python
from types_aiobotocore_finspace_data.literals import ApplicationPermissionType
```

Values:

- `AccessNotebooks`
- `CreateDataset`
- `GetTemporaryCredentials`
- `ManageAttributeSets`
- `ManageClusters`
- `ManageUsersAndGroups`
- `ViewAuditData`

<a id="changetypetype"></a>

## ChangeTypeType

```python
from types_aiobotocore_finspace_data.literals import ChangeTypeType
```

Values:

- `APPEND`
- `MODIFY`
- `REPLACE`

<a id="columndatatypetype"></a>

## ColumnDataTypeType

```python
from types_aiobotocore_finspace_data.literals import ColumnDataTypeType
```

Values:

- `BIGINT`
- `BINARY`
- `BOOLEAN`
- `CHAR`
- `DATE`
- `DATETIME`
- `DOUBLE`
- `FLOAT`
- `INTEGER`
- `SMALLINT`
- `STRING`
- `TINYINT`

<a id="dataviewstatustype"></a>

## DataViewStatusType

```python
from types_aiobotocore_finspace_data.literals import DataViewStatusType
```

Values:

- `CANCELLED`
- `FAILED`
- `FAILED_CLEANUP_FAILED`
- `PENDING`
- `RUNNING`
- `STARTING`
- `SUCCESS`
- `TIMEOUT`

<a id="datasetkindtype"></a>

## DatasetKindType

```python
from types_aiobotocore_finspace_data.literals import DatasetKindType
```

Values:

- `NON_TABULAR`
- `TABULAR`

<a id="datasetstatustype"></a>

## DatasetStatusType

```python
from types_aiobotocore_finspace_data.literals import DatasetStatusType
```

Values:

- `FAILED`
- `PENDING`
- `RUNNING`
- `SUCCESS`

<a id="errorcategorytype"></a>

## ErrorCategoryType

```python
from types_aiobotocore_finspace_data.literals import ErrorCategoryType
```

Values:

- `ACCESS_DENIED`
- `CANCELLED`
- `INTERNAL_SERVICE_EXCEPTION`
- `RESOURCE_NOT_FOUND`
- `SERVICE_QUOTA_EXCEEDED`
- `THROTTLING`
- `USER_RECOVERABLE`
- `VALIDATION`

<a id="exportfileformattype"></a>

## ExportFileFormatType

```python
from types_aiobotocore_finspace_data.literals import ExportFileFormatType
```

Values:

- `DELIMITED_TEXT`
- `PARQUET`

<a id="ingestionstatustype"></a>

## IngestionStatusType

```python
from types_aiobotocore_finspace_data.literals import IngestionStatusType
```

Values:

- `FAILED`
- `PENDING`
- `RUNNING`
- `STOP_REQUESTED`
- `SUCCESS`

<a id="listchangesetspaginatorname"></a>

## ListChangesetsPaginatorName

```python
from types_aiobotocore_finspace_data.literals import ListChangesetsPaginatorName
```

Values:

- `list_changesets`

<a id="listdataviewspaginatorname"></a>

## ListDataViewsPaginatorName

```python
from types_aiobotocore_finspace_data.literals import ListDataViewsPaginatorName
```

Values:

- `list_data_views`

<a id="listdatasetspaginatorname"></a>

## ListDatasetsPaginatorName

```python
from types_aiobotocore_finspace_data.literals import ListDatasetsPaginatorName
```

Values:

- `list_datasets`

<a id="listpermissiongroupspaginatorname"></a>

## ListPermissionGroupsPaginatorName

```python
from types_aiobotocore_finspace_data.literals import ListPermissionGroupsPaginatorName
```

Values:

- `list_permission_groups`

<a id="listuserspaginatorname"></a>

## ListUsersPaginatorName

```python
from types_aiobotocore_finspace_data.literals import ListUsersPaginatorName
```

Values:

- `list_users`

<a id="userstatustype"></a>

## UserStatusType

```python
from types_aiobotocore_finspace_data.literals import UserStatusType
```

Values:

- `CREATING`
- `DISABLED`
- `ENABLED`

<a id="usertypetype"></a>

## UserTypeType

```python
from types_aiobotocore_finspace_data.literals import UserTypeType
```

Values:

- `APP_USER`
- `SUPER_USER`

<a id="locationtypetype"></a>

## locationTypeType

```python
from types_aiobotocore_finspace_data.literals import locationTypeType
```

Values:

- `INGESTION`
- `SAGEMAKER`

<a id="finspacedataservicename"></a>

## FinSpaceDataServiceName

```python
from types_aiobotocore_finspace_data.literals import FinSpaceDataServiceName
```

Values:

- `finspace-data`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_finspace_data.literals import ServiceName
```

Values:

- `accessanalyzer`
- `account`
- `acm`
- `acm-pca`
- `alexaforbusiness`
- `amp`
- `amplify`
- `amplifybackend`
- `amplifyuibuilder`
- `apigateway`
- `apigatewaymanagementapi`
- `apigatewayv2`
- `appconfig`
- `appconfigdata`
- `appflow`
- `appintegrations`
- `application-autoscaling`
- `application-insights`
- `applicationcostprofiler`
- `appmesh`
- `apprunner`
- `appstream`
- `appsync`
- `athena`
- `auditmanager`
- `autoscaling`
- `autoscaling-plans`
- `backup`
- `backup-gateway`
- `batch`
- `billingconductor`
- `braket`
- `budgets`
- `ce`
- `chime`
- `chime-sdk-identity`
- `chime-sdk-meetings`
- `chime-sdk-messaging`
- `cloud9`
- `cloudcontrol`
- `clouddirectory`
- `cloudformation`
- `cloudfront`
- `cloudhsm`
- `cloudhsmv2`
- `cloudsearch`
- `cloudsearchdomain`
- `cloudtrail`
- `cloudwatch`
- `codeartifact`
- `codebuild`
- `codecommit`
- `codedeploy`
- `codeguru-reviewer`
- `codeguruprofiler`
- `codepipeline`
- `codestar`
- `codestar-connections`
- `codestar-notifications`
- `cognito-identity`
- `cognito-idp`
- `cognito-sync`
- `comprehend`
- `comprehendmedical`
- `compute-optimizer`
- `config`
- `connect`
- `connect-contact-lens`
- `connectparticipant`
- `cur`
- `customer-profiles`
- `databrew`
- `dataexchange`
- `datapipeline`
- `datasync`
- `dax`
- `detective`
- `devicefarm`
- `devops-guru`
- `directconnect`
- `discovery`
- `dlm`
- `dms`
- `docdb`
- `drs`
- `ds`
- `dynamodb`
- `dynamodbstreams`
- `ebs`
- `ec2`
- `ec2-instance-connect`
- `ecr`
- `ecr-public`
- `ecs`
- `efs`
- `eks`
- `elastic-inference`
- `elasticache`
- `elasticbeanstalk`
- `elastictranscoder`
- `elb`
- `elbv2`
- `emr`
- `emr-containers`
- `es`
- `events`
- `evidently`
- `finspace`
- `finspace-data`
- `firehose`
- `fis`
- `fms`
- `forecast`
- `forecastquery`
- `frauddetector`
- `fsx`
- `gamelift`
- `glacier`
- `globalaccelerator`
- `glue`
- `grafana`
- `greengrass`
- `greengrassv2`
- `groundstation`
- `guardduty`
- `health`
- `healthlake`
- `honeycode`
- `iam`
- `identitystore`
- `imagebuilder`
- `importexport`
- `inspector`
- `inspector2`
- `iot`
- `iot-data`
- `iot-jobs-data`
- `iot1click-devices`
- `iot1click-projects`
- `iotanalytics`
- `iotdeviceadvisor`
- `iotevents`
- `iotevents-data`
- `iotfleethub`
- `iotsecuretunneling`
- `iotsitewise`
- `iotthingsgraph`
- `iottwinmaker`
- `iotwireless`
- `ivs`
- `kafka`
- `kafkaconnect`
- `kendra`
- `keyspaces`
- `kinesis`
- `kinesis-video-archived-media`
- `kinesis-video-media`
- `kinesis-video-signaling`
- `kinesisanalytics`
- `kinesisanalyticsv2`
- `kinesisvideo`
- `kms`
- `lakeformation`
- `lambda`
- `lex-models`
- `lex-runtime`
- `lexv2-models`
- `lexv2-runtime`
- `license-manager`
- `lightsail`
- `location`
- `logs`
- `lookoutequipment`
- `lookoutmetrics`
- `lookoutvision`
- `machinelearning`
- `macie`
- `macie2`
- `managedblockchain`
- `marketplace-catalog`
- `marketplace-entitlement`
- `marketplacecommerceanalytics`
- `mediaconnect`
- `mediaconvert`
- `medialive`
- `mediapackage`
- `mediapackage-vod`
- `mediastore`
- `mediastore-data`
- `mediatailor`
- `memorydb`
- `meteringmarketplace`
- `mgh`
- `mgn`
- `migration-hub-refactor-spaces`
- `migrationhub-config`
- `migrationhubstrategy`
- `mobile`
- `mq`
- `mturk`
- `mwaa`
- `neptune`
- `network-firewall`
- `networkmanager`
- `nimble`
- `opensearch`
- `opsworks`
- `opsworkscm`
- `organizations`
- `outposts`
- `panorama`
- `personalize`
- `personalize-events`
- `personalize-runtime`
- `pi`
- `pinpoint`
- `pinpoint-email`
- `pinpoint-sms-voice`
- `polly`
- `pricing`
- `proton`
- `qldb`
- `qldb-session`
- `quicksight`
- `ram`
- `rbin`
- `rds`
- `rds-data`
- `redshift`
- `redshift-data`
- `rekognition`
- `resiliencehub`
- `resource-groups`
- `resourcegroupstaggingapi`
- `robomaker`
- `route53`
- `route53-recovery-cluster`
- `route53-recovery-control-config`
- `route53-recovery-readiness`
- `route53domains`
- `route53resolver`
- `rum`
- `s3`
- `s3control`
- `s3outposts`
- `sagemaker`
- `sagemaker-a2i-runtime`
- `sagemaker-edge`
- `sagemaker-featurestore-runtime`
- `sagemaker-runtime`
- `savingsplans`
- `schemas`
- `sdb`
- `secretsmanager`
- `securityhub`
- `serverlessrepo`
- `service-quotas`
- `servicecatalog`
- `servicecatalog-appregistry`
- `servicediscovery`
- `ses`
- `sesv2`
- `shield`
- `signer`
- `sms`
- `sms-voice`
- `snow-device-management`
- `snowball`
- `sns`
- `sqs`
- `ssm`
- `ssm-contacts`
- `ssm-incidents`
- `sso`
- `sso-admin`
- `sso-oidc`
- `stepfunctions`
- `storagegateway`
- `sts`
- `support`
- `swf`
- `synthetics`
- `textract`
- `timestream-query`
- `timestream-write`
- `transcribe`
- `transfer`
- `translate`
- `voice-id`
- `waf`
- `waf-regional`
- `wafv2`
- `wellarchitected`
- `wisdom`
- `workdocs`
- `worklink`
- `workmail`
- `workmailmessageflow`
- `workspaces`
- `workspaces-web`
- `xray`

<a id="resourceservicename"></a>

## ResourceServiceName

```python
from types_aiobotocore_finspace_data.literals import ResourceServiceName
```

Values:

- `cloudformation`
- `cloudwatch`
- `dynamodb`
- `ec2`
- `glacier`
- `iam`
- `opsworks`
- `s3`
- `sns`
- `sqs`

<a id="paginatorname"></a>

## PaginatorName

```python
from types_aiobotocore_finspace_data.literals import PaginatorName
```

Values:

- `list_changesets`
- `list_data_views`
- `list_datasets`
- `list_permission_groups`
- `list_users`
