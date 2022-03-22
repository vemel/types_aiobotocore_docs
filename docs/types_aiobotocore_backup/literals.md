<a id="literals-for-aiobotocore-backup-module"></a>

# Literals for aiobotocore Backup module

> [Index](../README.md) > [Backup](./README.md) > Literals

Auto-generated documentation for
[Backup](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
type annotations stubs module
[types-aiobotocore-backup](https://pypi.org/project/types-aiobotocore-backup/).

- [Literals for aiobotocore Backup module](#literals-for-aiobotocore-backup-module)
  - [BackupJobStateType](#backupjobstatetype)
  - [BackupVaultEventType](#backupvaulteventtype)
  - [ConditionTypeType](#conditiontypetype)
  - [CopyJobStateType](#copyjobstatetype)
  - [RecoveryPointStatusType](#recoverypointstatustype)
  - [RestoreJobStatusType](#restorejobstatustype)
  - [StorageClassType](#storageclasstype)
  - [BackupServiceName](#backupservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)

<a id="backupjobstatetype"></a>

## BackupJobStateType

```python
from types_aiobotocore_backup.literals import BackupJobStateType
```

Values:

- `ABORTED`
- `ABORTING`
- `COMPLETED`
- `CREATED`
- `EXPIRED`
- `FAILED`
- `PENDING`
- `RUNNING`

<a id="backupvaulteventtype"></a>

## BackupVaultEventType

```python
from types_aiobotocore_backup.literals import BackupVaultEventType
```

Values:

- `BACKUP_JOB_COMPLETED`
- `BACKUP_JOB_EXPIRED`
- `BACKUP_JOB_FAILED`
- `BACKUP_JOB_STARTED`
- `BACKUP_JOB_SUCCESSFUL`
- `BACKUP_PLAN_CREATED`
- `BACKUP_PLAN_MODIFIED`
- `COPY_JOB_FAILED`
- `COPY_JOB_STARTED`
- `COPY_JOB_SUCCESSFUL`
- `RECOVERY_POINT_MODIFIED`
- `RESTORE_JOB_COMPLETED`
- `RESTORE_JOB_FAILED`
- `RESTORE_JOB_STARTED`
- `RESTORE_JOB_SUCCESSFUL`
- `S3_BACKUP_OBJECT_FAILED`
- `S3_RESTORE_OBJECT_FAILED`

<a id="conditiontypetype"></a>

## ConditionTypeType

```python
from types_aiobotocore_backup.literals import ConditionTypeType
```

Values:

- `STRINGEQUALS`

<a id="copyjobstatetype"></a>

## CopyJobStateType

```python
from types_aiobotocore_backup.literals import CopyJobStateType
```

Values:

- `COMPLETED`
- `CREATED`
- `FAILED`
- `RUNNING`

<a id="recoverypointstatustype"></a>

## RecoveryPointStatusType

```python
from types_aiobotocore_backup.literals import RecoveryPointStatusType
```

Values:

- `COMPLETED`
- `DELETING`
- `EXPIRED`
- `PARTIAL`

<a id="restorejobstatustype"></a>

## RestoreJobStatusType

```python
from types_aiobotocore_backup.literals import RestoreJobStatusType
```

Values:

- `ABORTED`
- `COMPLETED`
- `FAILED`
- `PENDING`
- `RUNNING`

<a id="storageclasstype"></a>

## StorageClassType

```python
from types_aiobotocore_backup.literals import StorageClassType
```

Values:

- `COLD`
- `DELETED`
- `WARM`

<a id="backupservicename"></a>

## BackupServiceName

```python
from types_aiobotocore_backup.literals import BackupServiceName
```

Values:

- `backup`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_backup.literals import ServiceName
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
from types_aiobotocore_backup.literals import ResourceServiceName
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
