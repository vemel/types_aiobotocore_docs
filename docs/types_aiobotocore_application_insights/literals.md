<a id="literals-for-aiobotocore-applicationinsights-module"></a>

# Literals for aiobotocore ApplicationInsights module

> [Index](../README.md) > [ApplicationInsights](./README.md) > Literals

Auto-generated documentation for
[ApplicationInsights](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
type annotations stubs module
[types-aiobotocore-application-insights](https://pypi.org/project/types-aiobotocore-application-insights/).

- [Literals for aiobotocore ApplicationInsights module](#literals-for-aiobotocore-applicationinsights-module)
  - [CloudWatchEventSourceType](#cloudwatcheventsourcetype)
  - [ConfigurationEventResourceTypeType](#configurationeventresourcetypetype)
  - [ConfigurationEventStatusType](#configurationeventstatustype)
  - [DiscoveryTypeType](#discoverytypetype)
  - [FeedbackKeyType](#feedbackkeytype)
  - [FeedbackValueType](#feedbackvaluetype)
  - [LogFilterType](#logfiltertype)
  - [OsTypeType](#ostypetype)
  - [SeverityLevelType](#severityleveltype)
  - [StatusType](#statustype)
  - [TierType](#tiertype)
  - [ApplicationInsightsServiceName](#applicationinsightsservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)

<a id="cloudwatcheventsourcetype"></a>

## CloudWatchEventSourceType

```python
from types_aiobotocore_application_insights.literals import CloudWatchEventSourceType
```

Values:

- `CODE_DEPLOY`
- `EC2`
- `HEALTH`
- `RDS`

<a id="configurationeventresourcetypetype"></a>

## ConfigurationEventResourceTypeType

```python
from types_aiobotocore_application_insights.literals import ConfigurationEventResourceTypeType
```

Values:

- `CLOUDFORMATION`
- `CLOUDWATCH_ALARM`
- `CLOUDWATCH_LOG`
- `SSM_ASSOCIATION`

<a id="configurationeventstatustype"></a>

## ConfigurationEventStatusType

```python
from types_aiobotocore_application_insights.literals import ConfigurationEventStatusType
```

Values:

- `ERROR`
- `INFO`
- `WARN`

<a id="discoverytypetype"></a>

## DiscoveryTypeType

```python
from types_aiobotocore_application_insights.literals import DiscoveryTypeType
```

Values:

- `ACCOUNT_BASED`
- `RESOURCE_GROUP_BASED`

<a id="feedbackkeytype"></a>

## FeedbackKeyType

```python
from types_aiobotocore_application_insights.literals import FeedbackKeyType
```

Values:

- `INSIGHTS_FEEDBACK`

<a id="feedbackvaluetype"></a>

## FeedbackValueType

```python
from types_aiobotocore_application_insights.literals import FeedbackValueType
```

Values:

- `NOT_SPECIFIED`
- `NOT_USEFUL`
- `USEFUL`

<a id="logfiltertype"></a>

## LogFilterType

```python
from types_aiobotocore_application_insights.literals import LogFilterType
```

Values:

- `ERROR`
- `INFO`
- `WARN`

<a id="ostypetype"></a>

## OsTypeType

```python
from types_aiobotocore_application_insights.literals import OsTypeType
```

Values:

- `LINUX`
- `WINDOWS`

<a id="severityleveltype"></a>

## SeverityLevelType

```python
from types_aiobotocore_application_insights.literals import SeverityLevelType
```

Values:

- `High`
- `Low`
- `Medium`

<a id="statustype"></a>

## StatusType

```python
from types_aiobotocore_application_insights.literals import StatusType
```

Values:

- `IGNORE`
- `PENDING`
- `RECURRING`
- `RESOLVED`

<a id="tiertype"></a>

## TierType

```python
from types_aiobotocore_application_insights.literals import TierType
```

Values:

- `ACTIVE_DIRECTORY`
- `CUSTOM`
- `DEFAULT`
- `DOT_NET_CORE`
- `DOT_NET_WEB`
- `DOT_NET_WEB_TIER`
- `DOT_NET_WORKER`
- `JAVA_JMX`
- `MYSQL`
- `ORACLE`
- `POSTGRESQL`
- `SAP_HANA_HIGH_AVAILABILITY`
- `SAP_HANA_MULTI_NODE`
- `SAP_HANA_SINGLE_NODE`
- `SHAREPOINT`
- `SQL_SERVER`
- `SQL_SERVER_ALWAYSON_AVAILABILITY_GROUP`
- `SQL_SERVER_FAILOVER_CLUSTER_INSTANCE`

<a id="applicationinsightsservicename"></a>

## ApplicationInsightsServiceName

```python
from types_aiobotocore_application_insights.literals import ApplicationInsightsServiceName
```

Values:

- `application-insights`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_application_insights.literals import ServiceName
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
from types_aiobotocore_application_insights.literals import ResourceServiceName
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
