<a id="literals-for-aiobotocore-cloudtrail-module"></a>

# Literals for aiobotocore CloudTrail module

> [Index](../README.md) > [CloudTrail](./README.md) > Literals

Auto-generated documentation for
[CloudTrail](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail.html#CloudTrail)
type annotations stubs module
[types-aiobotocore-cloudtrail](https://pypi.org/project/types-aiobotocore-cloudtrail/).

- [Literals for aiobotocore CloudTrail module](#literals-for-aiobotocore-cloudtrail-module)
  - [EventCategoryType](#eventcategorytype)
  - [EventDataStoreStatusType](#eventdatastorestatustype)
  - [InsightTypeType](#insighttypetype)
  - [ListPublicKeysPaginatorName](#listpublickeyspaginatorname)
  - [ListTagsPaginatorName](#listtagspaginatorname)
  - [ListTrailsPaginatorName](#listtrailspaginatorname)
  - [LookupAttributeKeyType](#lookupattributekeytype)
  - [LookupEventsPaginatorName](#lookupeventspaginatorname)
  - [QueryStatusType](#querystatustype)
  - [ReadWriteTypeType](#readwritetypetype)
  - [CloudTrailServiceName](#cloudtrailservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="eventcategorytype"></a>

## EventCategoryType

```python
from types_aiobotocore_cloudtrail.literals import EventCategoryType
```

Values:

- `insight`

<a id="eventdatastorestatustype"></a>

## EventDataStoreStatusType

```python
from types_aiobotocore_cloudtrail.literals import EventDataStoreStatusType
```

Values:

- `CREATED`
- `ENABLED`
- `PENDING_DELETION`

<a id="insighttypetype"></a>

## InsightTypeType

```python
from types_aiobotocore_cloudtrail.literals import InsightTypeType
```

Values:

- `ApiCallRateInsight`
- `ApiErrorRateInsight`

<a id="listpublickeyspaginatorname"></a>

## ListPublicKeysPaginatorName

```python
from types_aiobotocore_cloudtrail.literals import ListPublicKeysPaginatorName
```

Values:

- `list_public_keys`

<a id="listtagspaginatorname"></a>

## ListTagsPaginatorName

```python
from types_aiobotocore_cloudtrail.literals import ListTagsPaginatorName
```

Values:

- `list_tags`

<a id="listtrailspaginatorname"></a>

## ListTrailsPaginatorName

```python
from types_aiobotocore_cloudtrail.literals import ListTrailsPaginatorName
```

Values:

- `list_trails`

<a id="lookupattributekeytype"></a>

## LookupAttributeKeyType

```python
from types_aiobotocore_cloudtrail.literals import LookupAttributeKeyType
```

Values:

- `AccessKeyId`
- `EventId`
- `EventName`
- `EventSource`
- `ReadOnly`
- `ResourceName`
- `ResourceType`
- `Username`

<a id="lookupeventspaginatorname"></a>

## LookupEventsPaginatorName

```python
from types_aiobotocore_cloudtrail.literals import LookupEventsPaginatorName
```

Values:

- `lookup_events`

<a id="querystatustype"></a>

## QueryStatusType

```python
from types_aiobotocore_cloudtrail.literals import QueryStatusType
```

Values:

- `CANCELLED`
- `FAILED`
- `FINISHED`
- `QUEUED`
- `RUNNING`
- `TIMED_OUT`

<a id="readwritetypetype"></a>

## ReadWriteTypeType

```python
from types_aiobotocore_cloudtrail.literals import ReadWriteTypeType
```

Values:

- `All`
- `ReadOnly`
- `WriteOnly`

<a id="cloudtrailservicename"></a>

## CloudTrailServiceName

```python
from types_aiobotocore_cloudtrail.literals import CloudTrailServiceName
```

Values:

- `cloudtrail`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_cloudtrail.literals import ServiceName
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
from types_aiobotocore_cloudtrail.literals import ResourceServiceName
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
from types_aiobotocore_cloudtrail.literals import PaginatorName
```

Values:

- `list_public_keys`
- `list_tags`
- `list_trails`
- `lookup_events`
