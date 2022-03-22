<a id="literals-for-aiobotocore-efs-module"></a>

# Literals for aiobotocore EFS module

> [Index](../README.md) > [EFS](./README.md) > Literals

Auto-generated documentation for
[EFS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
type annotations stubs module
[types-aiobotocore-efs](https://pypi.org/project/types-aiobotocore-efs/).

- [Literals for aiobotocore EFS module](#literals-for-aiobotocore-efs-module)
  - [DescribeFileSystemsPaginatorName](#describefilesystemspaginatorname)
  - [DescribeMountTargetsPaginatorName](#describemounttargetspaginatorname)
  - [DescribeTagsPaginatorName](#describetagspaginatorname)
  - [LifeCycleStateType](#lifecyclestatetype)
  - [PerformanceModeType](#performancemodetype)
  - [ReplicationStatusType](#replicationstatustype)
  - [ResourceIdTypeType](#resourceidtypetype)
  - [ResourceType](#resourcetype)
  - [StatusType](#statustype)
  - [ThroughputModeType](#throughputmodetype)
  - [TransitionToIARulesType](#transitiontoiarulestype)
  - [TransitionToPrimaryStorageClassRulesType](#transitiontoprimarystorageclassrulestype)
  - [EFSServiceName](#efsservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="describefilesystemspaginatorname"></a>

## DescribeFileSystemsPaginatorName

```python
from types_aiobotocore_efs.literals import DescribeFileSystemsPaginatorName
```

Values:

- `describe_file_systems`

<a id="describemounttargetspaginatorname"></a>

## DescribeMountTargetsPaginatorName

```python
from types_aiobotocore_efs.literals import DescribeMountTargetsPaginatorName
```

Values:

- `describe_mount_targets`

<a id="describetagspaginatorname"></a>

## DescribeTagsPaginatorName

```python
from types_aiobotocore_efs.literals import DescribeTagsPaginatorName
```

Values:

- `describe_tags`

<a id="lifecyclestatetype"></a>

## LifeCycleStateType

```python
from types_aiobotocore_efs.literals import LifeCycleStateType
```

Values:

- `available`
- `creating`
- `deleted`
- `deleting`
- `error`
- `updating`

<a id="performancemodetype"></a>

## PerformanceModeType

```python
from types_aiobotocore_efs.literals import PerformanceModeType
```

Values:

- `generalPurpose`
- `maxIO`

<a id="replicationstatustype"></a>

## ReplicationStatusType

```python
from types_aiobotocore_efs.literals import ReplicationStatusType
```

Values:

- `DELETING`
- `ENABLED`
- `ENABLING`
- `ERROR`

<a id="resourceidtypetype"></a>

## ResourceIdTypeType

```python
from types_aiobotocore_efs.literals import ResourceIdTypeType
```

Values:

- `LONG_ID`
- `SHORT_ID`

<a id="resourcetype"></a>

## ResourceType

```python
from types_aiobotocore_efs.literals import ResourceType
```

Values:

- `FILE_SYSTEM`
- `MOUNT_TARGET`

<a id="statustype"></a>

## StatusType

```python
from types_aiobotocore_efs.literals import StatusType
```

Values:

- `DISABLED`
- `DISABLING`
- `ENABLED`
- `ENABLING`

<a id="throughputmodetype"></a>

## ThroughputModeType

```python
from types_aiobotocore_efs.literals import ThroughputModeType
```

Values:

- `bursting`
- `provisioned`

<a id="transitiontoiarulestype"></a>

## TransitionToIARulesType

```python
from types_aiobotocore_efs.literals import TransitionToIARulesType
```

Values:

- `AFTER_14_DAYS`
- `AFTER_30_DAYS`
- `AFTER_60_DAYS`
- `AFTER_7_DAYS`
- `AFTER_90_DAYS`

<a id="transitiontoprimarystorageclassrulestype"></a>

## TransitionToPrimaryStorageClassRulesType

```python
from types_aiobotocore_efs.literals import TransitionToPrimaryStorageClassRulesType
```

Values:

- `AFTER_1_ACCESS`

<a id="efsservicename"></a>

## EFSServiceName

```python
from types_aiobotocore_efs.literals import EFSServiceName
```

Values:

- `efs`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_efs.literals import ServiceName
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
from types_aiobotocore_efs.literals import ResourceServiceName
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
from types_aiobotocore_efs.literals import PaginatorName
```

Values:

- `describe_file_systems`
- `describe_mount_targets`
- `describe_tags`
