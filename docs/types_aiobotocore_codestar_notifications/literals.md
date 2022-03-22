<a id="literals-for-aiobotocore-codestarnotifications-module"></a>

# Literals for aiobotocore CodeStarNotifications module

> [Index](../README.md) > [CodeStarNotifications](./README.md) > Literals

Auto-generated documentation for
[CodeStarNotifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
type annotations stubs module
[types-aiobotocore-codestar-notifications](https://pypi.org/project/types-aiobotocore-codestar-notifications/).

- [Literals for aiobotocore CodeStarNotifications module](#literals-for-aiobotocore-codestarnotifications-module)
  - [DetailTypeType](#detailtypetype)
  - [ListEventTypesFilterNameType](#listeventtypesfilternametype)
  - [ListEventTypesPaginatorName](#listeventtypespaginatorname)
  - [ListNotificationRulesFilterNameType](#listnotificationrulesfilternametype)
  - [ListNotificationRulesPaginatorName](#listnotificationrulespaginatorname)
  - [ListTargetsFilterNameType](#listtargetsfilternametype)
  - [ListTargetsPaginatorName](#listtargetspaginatorname)
  - [NotificationRuleStatusType](#notificationrulestatustype)
  - [TargetStatusType](#targetstatustype)
  - [CodeStarNotificationsServiceName](#codestarnotificationsservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="detailtypetype"></a>

## DetailTypeType

```python
from types_aiobotocore_codestar_notifications.literals import DetailTypeType
```

Values:

- `BASIC`
- `FULL`

<a id="listeventtypesfilternametype"></a>

## ListEventTypesFilterNameType

```python
from types_aiobotocore_codestar_notifications.literals import ListEventTypesFilterNameType
```

Values:

- `RESOURCE_TYPE`
- `SERVICE_NAME`

<a id="listeventtypespaginatorname"></a>

## ListEventTypesPaginatorName

```python
from types_aiobotocore_codestar_notifications.literals import ListEventTypesPaginatorName
```

Values:

- `list_event_types`

<a id="listnotificationrulesfilternametype"></a>

## ListNotificationRulesFilterNameType

```python
from types_aiobotocore_codestar_notifications.literals import ListNotificationRulesFilterNameType
```

Values:

- `CREATED_BY`
- `EVENT_TYPE_ID`
- `RESOURCE`
- `TARGET_ADDRESS`

<a id="listnotificationrulespaginatorname"></a>

## ListNotificationRulesPaginatorName

```python
from types_aiobotocore_codestar_notifications.literals import ListNotificationRulesPaginatorName
```

Values:

- `list_notification_rules`

<a id="listtargetsfilternametype"></a>

## ListTargetsFilterNameType

```python
from types_aiobotocore_codestar_notifications.literals import ListTargetsFilterNameType
```

Values:

- `TARGET_ADDRESS`
- `TARGET_STATUS`
- `TARGET_TYPE`

<a id="listtargetspaginatorname"></a>

## ListTargetsPaginatorName

```python
from types_aiobotocore_codestar_notifications.literals import ListTargetsPaginatorName
```

Values:

- `list_targets`

<a id="notificationrulestatustype"></a>

## NotificationRuleStatusType

```python
from types_aiobotocore_codestar_notifications.literals import NotificationRuleStatusType
```

Values:

- `DISABLED`
- `ENABLED`

<a id="targetstatustype"></a>

## TargetStatusType

```python
from types_aiobotocore_codestar_notifications.literals import TargetStatusType
```

Values:

- `ACTIVE`
- `DEACTIVATED`
- `INACTIVE`
- `PENDING`
- `UNREACHABLE`

<a id="codestarnotificationsservicename"></a>

## CodeStarNotificationsServiceName

```python
from types_aiobotocore_codestar_notifications.literals import CodeStarNotificationsServiceName
```

Values:

- `codestar-notifications`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_codestar_notifications.literals import ServiceName
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
from types_aiobotocore_codestar_notifications.literals import ResourceServiceName
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
from types_aiobotocore_codestar_notifications.literals import PaginatorName
```

Values:

- `list_event_types`
- `list_notification_rules`
- `list_targets`
