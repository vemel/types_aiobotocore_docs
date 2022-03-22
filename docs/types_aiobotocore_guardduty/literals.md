<a id="literals-for-aiobotocore-guardduty-module"></a>

# Literals for aiobotocore GuardDuty module

> [Index](../README.md) > [GuardDuty](./README.md) > Literals

Auto-generated documentation for
[GuardDuty](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
type annotations stubs module
[types-aiobotocore-guardduty](https://pypi.org/project/types-aiobotocore-guardduty/).

- [Literals for aiobotocore GuardDuty module](#literals-for-aiobotocore-guardduty-module)
  - [AdminStatusType](#adminstatustype)
  - [DataSourceStatusType](#datasourcestatustype)
  - [DataSourceType](#datasourcetype)
  - [DestinationTypeType](#destinationtypetype)
  - [DetectorStatusType](#detectorstatustype)
  - [FeedbackType](#feedbacktype)
  - [FilterActionType](#filteractiontype)
  - [FindingPublishingFrequencyType](#findingpublishingfrequencytype)
  - [FindingStatisticTypeType](#findingstatistictypetype)
  - [IpSetFormatType](#ipsetformattype)
  - [IpSetStatusType](#ipsetstatustype)
  - [ListDetectorsPaginatorName](#listdetectorspaginatorname)
  - [ListFiltersPaginatorName](#listfilterspaginatorname)
  - [ListFindingsPaginatorName](#listfindingspaginatorname)
  - [ListIPSetsPaginatorName](#listipsetspaginatorname)
  - [ListInvitationsPaginatorName](#listinvitationspaginatorname)
  - [ListMembersPaginatorName](#listmemberspaginatorname)
  - [ListOrganizationAdminAccountsPaginatorName](#listorganizationadminaccountspaginatorname)
  - [ListThreatIntelSetsPaginatorName](#listthreatintelsetspaginatorname)
  - [OrderByType](#orderbytype)
  - [PublishingStatusType](#publishingstatustype)
  - [ThreatIntelSetFormatType](#threatintelsetformattype)
  - [ThreatIntelSetStatusType](#threatintelsetstatustype)
  - [UsageStatisticTypeType](#usagestatistictypetype)
  - [GuardDutyServiceName](#guarddutyservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="adminstatustype"></a>

## AdminStatusType

```python
from types_aiobotocore_guardduty.literals import AdminStatusType
```

Values:

- `DISABLE_IN_PROGRESS`
- `ENABLED`

<a id="datasourcestatustype"></a>

## DataSourceStatusType

```python
from types_aiobotocore_guardduty.literals import DataSourceStatusType
```

Values:

- `DISABLED`
- `ENABLED`

<a id="datasourcetype"></a>

## DataSourceType

```python
from types_aiobotocore_guardduty.literals import DataSourceType
```

Values:

- `CLOUD_TRAIL`
- `DNS_LOGS`
- `FLOW_LOGS`
- `KUBERNETES_AUDIT_LOGS`
- `S3_LOGS`

<a id="destinationtypetype"></a>

## DestinationTypeType

```python
from types_aiobotocore_guardduty.literals import DestinationTypeType
```

Values:

- `S3`

<a id="detectorstatustype"></a>

## DetectorStatusType

```python
from types_aiobotocore_guardduty.literals import DetectorStatusType
```

Values:

- `DISABLED`
- `ENABLED`

<a id="feedbacktype"></a>

## FeedbackType

```python
from types_aiobotocore_guardduty.literals import FeedbackType
```

Values:

- `NOT_USEFUL`
- `USEFUL`

<a id="filteractiontype"></a>

## FilterActionType

```python
from types_aiobotocore_guardduty.literals import FilterActionType
```

Values:

- `ARCHIVE`
- `NOOP`

<a id="findingpublishingfrequencytype"></a>

## FindingPublishingFrequencyType

```python
from types_aiobotocore_guardduty.literals import FindingPublishingFrequencyType
```

Values:

- `FIFTEEN_MINUTES`
- `ONE_HOUR`
- `SIX_HOURS`

<a id="findingstatistictypetype"></a>

## FindingStatisticTypeType

```python
from types_aiobotocore_guardduty.literals import FindingStatisticTypeType
```

Values:

- `COUNT_BY_SEVERITY`

<a id="ipsetformattype"></a>

## IpSetFormatType

```python
from types_aiobotocore_guardduty.literals import IpSetFormatType
```

Values:

- `ALIEN_VAULT`
- `FIRE_EYE`
- `OTX_CSV`
- `PROOF_POINT`
- `STIX`
- `TXT`

<a id="ipsetstatustype"></a>

## IpSetStatusType

```python
from types_aiobotocore_guardduty.literals import IpSetStatusType
```

Values:

- `ACTIVATING`
- `ACTIVE`
- `DEACTIVATING`
- `DELETE_PENDING`
- `DELETED`
- `ERROR`
- `INACTIVE`

<a id="listdetectorspaginatorname"></a>

## ListDetectorsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListDetectorsPaginatorName
```

Values:

- `list_detectors`

<a id="listfilterspaginatorname"></a>

## ListFiltersPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListFiltersPaginatorName
```

Values:

- `list_filters`

<a id="listfindingspaginatorname"></a>

## ListFindingsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListFindingsPaginatorName
```

Values:

- `list_findings`

<a id="listipsetspaginatorname"></a>

## ListIPSetsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListIPSetsPaginatorName
```

Values:

- `list_ip_sets`

<a id="listinvitationspaginatorname"></a>

## ListInvitationsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListInvitationsPaginatorName
```

Values:

- `list_invitations`

<a id="listmemberspaginatorname"></a>

## ListMembersPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListMembersPaginatorName
```

Values:

- `list_members`

<a id="listorganizationadminaccountspaginatorname"></a>

## ListOrganizationAdminAccountsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListOrganizationAdminAccountsPaginatorName
```

Values:

- `list_organization_admin_accounts`

<a id="listthreatintelsetspaginatorname"></a>

## ListThreatIntelSetsPaginatorName

```python
from types_aiobotocore_guardduty.literals import ListThreatIntelSetsPaginatorName
```

Values:

- `list_threat_intel_sets`

<a id="orderbytype"></a>

## OrderByType

```python
from types_aiobotocore_guardduty.literals import OrderByType
```

Values:

- `ASC`
- `DESC`

<a id="publishingstatustype"></a>

## PublishingStatusType

```python
from types_aiobotocore_guardduty.literals import PublishingStatusType
```

Values:

- `PENDING_VERIFICATION`
- `PUBLISHING`
- `STOPPED`
- `UNABLE_TO_PUBLISH_FIX_DESTINATION_PROPERTY`

<a id="threatintelsetformattype"></a>

## ThreatIntelSetFormatType

```python
from types_aiobotocore_guardduty.literals import ThreatIntelSetFormatType
```

Values:

- `ALIEN_VAULT`
- `FIRE_EYE`
- `OTX_CSV`
- `PROOF_POINT`
- `STIX`
- `TXT`

<a id="threatintelsetstatustype"></a>

## ThreatIntelSetStatusType

```python
from types_aiobotocore_guardduty.literals import ThreatIntelSetStatusType
```

Values:

- `ACTIVATING`
- `ACTIVE`
- `DEACTIVATING`
- `DELETE_PENDING`
- `DELETED`
- `ERROR`
- `INACTIVE`

<a id="usagestatistictypetype"></a>

## UsageStatisticTypeType

```python
from types_aiobotocore_guardduty.literals import UsageStatisticTypeType
```

Values:

- `SUM_BY_ACCOUNT`
- `SUM_BY_DATA_SOURCE`
- `SUM_BY_RESOURCE`
- `TOP_RESOURCES`

<a id="guarddutyservicename"></a>

## GuardDutyServiceName

```python
from types_aiobotocore_guardduty.literals import GuardDutyServiceName
```

Values:

- `guardduty`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_guardduty.literals import ServiceName
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
from types_aiobotocore_guardduty.literals import ResourceServiceName
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
from types_aiobotocore_guardduty.literals import PaginatorName
```

Values:

- `list_detectors`
- `list_filters`
- `list_findings`
- `list_invitations`
- `list_ip_sets`
- `list_members`
- `list_organization_admin_accounts`
- `list_threat_intel_sets`
