<a id="literals-for-aiobotocore-kinesisvideo-module"></a>

# Literals for aiobotocore KinesisVideo module

> [Index](..) > [KinesisVideo](.) > Literals

Auto-generated documentation for
[KinesisVideo](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisvideo.html#KinesisVideo)
type annotations stubs module
[types-aiobotocore-kinesisvideo](https://pypi.org/project/types-aiobotocore-kinesisvideo/).

- [Literals for aiobotocore KinesisVideo module](#literals-for-aiobotocore-kinesisvideo-module)
  - [APINameType](#apinametype)
  - [ChannelProtocolType](#channelprotocoltype)
  - [ChannelRoleType](#channelroletype)
  - [ChannelTypeType](#channeltypetype)
  - [ComparisonOperatorType](#comparisonoperatortype)
  - [ListSignalingChannelsPaginatorName](#listsignalingchannelspaginatorname)
  - [ListStreamsPaginatorName](#liststreamspaginatorname)
  - [StatusType](#statustype)
  - [UpdateDataRetentionOperationType](#updatedataretentionoperationtype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="apinametype"></a>

## APINameType

```python
from types_aiobotocore_kinesisvideo.literals import APINameType
```

Values:

- `GET_CLIP`
- `GET_DASH_STREAMING_SESSION_URL`
- `GET_HLS_STREAMING_SESSION_URL`
- `GET_MEDIA`
- `GET_MEDIA_FOR_FRAGMENT_LIST`
- `LIST_FRAGMENTS`
- `PUT_MEDIA`

<a id="channelprotocoltype"></a>

## ChannelProtocolType

```python
from types_aiobotocore_kinesisvideo.literals import ChannelProtocolType
```

Values:

- `HTTPS`
- `WSS`

<a id="channelroletype"></a>

## ChannelRoleType

```python
from types_aiobotocore_kinesisvideo.literals import ChannelRoleType
```

Values:

- `MASTER`
- `VIEWER`

<a id="channeltypetype"></a>

## ChannelTypeType

```python
from types_aiobotocore_kinesisvideo.literals import ChannelTypeType
```

Values:

- `SINGLE_MASTER`

<a id="comparisonoperatortype"></a>

## ComparisonOperatorType

```python
from types_aiobotocore_kinesisvideo.literals import ComparisonOperatorType
```

Values:

- `BEGINS_WITH`

<a id="listsignalingchannelspaginatorname"></a>

## ListSignalingChannelsPaginatorName

```python
from types_aiobotocore_kinesisvideo.literals import ListSignalingChannelsPaginatorName
```

Values:

- `list_signaling_channels`

<a id="liststreamspaginatorname"></a>

## ListStreamsPaginatorName

```python
from types_aiobotocore_kinesisvideo.literals import ListStreamsPaginatorName
```

Values:

- `list_streams`

<a id="statustype"></a>

## StatusType

```python
from types_aiobotocore_kinesisvideo.literals import StatusType
```

Values:

- `ACTIVE`
- `CREATING`
- `DELETING`
- `UPDATING`

<a id="updatedataretentionoperationtype"></a>

## UpdateDataRetentionOperationType

```python
from types_aiobotocore_kinesisvideo.literals import UpdateDataRetentionOperationType
```

Values:

- `DECREASE_DATA_RETENTION`
- `INCREASE_DATA_RETENTION`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_kinesisvideo.literals import ServiceName
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

<a id="paginatorname"></a>

## PaginatorName

```python
from types_aiobotocore_kinesisvideo.literals import PaginatorName
```

Values:

- `list_signaling_channels`
- `list_streams`
