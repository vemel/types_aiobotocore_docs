<a id="literals-for-aiobotocore-iotwireless-module"></a>

# Literals for aiobotocore IoTWireless module

> [Index](..) > [IoTWireless](.) > Literals

Auto-generated documentation for
[IoTWireless](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
type annotations stubs module
[types-aiobotocore-iotwireless](https://pypi.org/project/types-aiobotocore-iotwireless/).

- [Literals for aiobotocore IoTWireless module](#literals-for-aiobotocore-iotwireless-module)
  - [BatteryLevelType](#batteryleveltype)
  - [ConnectionStatusType](#connectionstatustype)
  - [DeviceStateType](#devicestatetype)
  - [DlClassType](#dlclasstype)
  - [EventNotificationPartnerTypeType](#eventnotificationpartnertypetype)
  - [EventNotificationTopicStatusType](#eventnotificationtopicstatustype)
  - [EventType](#eventtype)
  - [ExpressionTypeType](#expressiontypetype)
  - [FuotaDeviceStatusType](#fuotadevicestatustype)
  - [FuotaTaskStatusType](#fuotataskstatustype)
  - [IdentifierTypeType](#identifiertypetype)
  - [LogLevelType](#logleveltype)
  - [MessageTypeType](#messagetypetype)
  - [PartnerTypeType](#partnertypetype)
  - [SigningAlgType](#signingalgtype)
  - [SupportedRfRegionType](#supportedrfregiontype)
  - [WirelessDeviceEventType](#wirelessdeviceeventtype)
  - [WirelessDeviceFrameInfoType](#wirelessdeviceframeinfotype)
  - [WirelessDeviceIdTypeType](#wirelessdeviceidtypetype)
  - [WirelessDeviceTypeType](#wirelessdevicetypetype)
  - [WirelessGatewayEventType](#wirelessgatewayeventtype)
  - [WirelessGatewayIdTypeType](#wirelessgatewayidtypetype)
  - [WirelessGatewayServiceTypeType](#wirelessgatewayservicetypetype)
  - [WirelessGatewayTaskDefinitionTypeType](#wirelessgatewaytaskdefinitiontypetype)
  - [WirelessGatewayTaskStatusType](#wirelessgatewaytaskstatustype)
  - [WirelessGatewayTypeType](#wirelessgatewaytypetype)
  - [ServiceName](#servicename)

<a id="batteryleveltype"></a>

## BatteryLevelType

```python
from types_aiobotocore_iotwireless.literals import BatteryLevelType
```

Values:

- `critical`
- `low`
- `normal`

<a id="connectionstatustype"></a>

## ConnectionStatusType

```python
from types_aiobotocore_iotwireless.literals import ConnectionStatusType
```

Values:

- `Connected`
- `Disconnected`

<a id="devicestatetype"></a>

## DeviceStateType

```python
from types_aiobotocore_iotwireless.literals import DeviceStateType
```

Values:

- `Provisioned`
- `RegisteredNotSeen`
- `RegisteredReachable`
- `RegisteredUnreachable`

<a id="dlclasstype"></a>

## DlClassType

```python
from types_aiobotocore_iotwireless.literals import DlClassType
```

Values:

- `ClassB`
- `ClassC`

<a id="eventnotificationpartnertypetype"></a>

## EventNotificationPartnerTypeType

```python
from types_aiobotocore_iotwireless.literals import EventNotificationPartnerTypeType
```

Values:

- `Sidewalk`

<a id="eventnotificationtopicstatustype"></a>

## EventNotificationTopicStatusType

```python
from types_aiobotocore_iotwireless.literals import EventNotificationTopicStatusType
```

Values:

- `Disabled`
- `Enabled`

<a id="eventtype"></a>

## EventType

```python
from types_aiobotocore_iotwireless.literals import EventType
```

Values:

- `ack`
- `discovered`
- `lost`
- `nack`
- `passthrough`

<a id="expressiontypetype"></a>

## ExpressionTypeType

```python
from types_aiobotocore_iotwireless.literals import ExpressionTypeType
```

Values:

- `MqttTopic`
- `RuleName`

<a id="fuotadevicestatustype"></a>

## FuotaDeviceStatusType

```python
from types_aiobotocore_iotwireless.literals import FuotaDeviceStatusType
```

Values:

- `FragAlgo_unsupported`
- `FragIndex_unsupported`
- `Initial`
- `MemoryError`
- `MICError`
- `MissingFrag`
- `Not_enough_memory`
- `Package_Not_Supported`
- `SessionCnt_replay`
- `Successful`
- `Wrong_descriptor`

<a id="fuotataskstatustype"></a>

## FuotaTaskStatusType

```python
from types_aiobotocore_iotwireless.literals import FuotaTaskStatusType
```

Values:

- `Delete_Waiting`
- `FuotaDone`
- `FuotaSession_Waiting`
- `In_FuotaSession`
- `Pending`

<a id="identifiertypetype"></a>

## IdentifierTypeType

```python
from types_aiobotocore_iotwireless.literals import IdentifierTypeType
```

Values:

- `PartnerAccountId`

<a id="logleveltype"></a>

## LogLevelType

```python
from types_aiobotocore_iotwireless.literals import LogLevelType
```

Values:

- `DISABLED`
- `ERROR`
- `INFO`

<a id="messagetypetype"></a>

## MessageTypeType

```python
from types_aiobotocore_iotwireless.literals import MessageTypeType
```

Values:

- `CUSTOM_COMMAND_ID_GET`
- `CUSTOM_COMMAND_ID_NOTIFY`
- `CUSTOM_COMMAND_ID_RESP`
- `CUSTOM_COMMAND_ID_SET`

<a id="partnertypetype"></a>

## PartnerTypeType

```python
from types_aiobotocore_iotwireless.literals import PartnerTypeType
```

Values:

- `Sidewalk`

<a id="signingalgtype"></a>

## SigningAlgType

```python
from types_aiobotocore_iotwireless.literals import SigningAlgType
```

Values:

- `Ed25519`
- `P256r1`

<a id="supportedrfregiontype"></a>

## SupportedRfRegionType

```python
from types_aiobotocore_iotwireless.literals import SupportedRfRegionType
```

Values:

- `AS923-1`
- `AU915`
- `EU868`
- `US915`

<a id="wirelessdeviceeventtype"></a>

## WirelessDeviceEventType

```python
from types_aiobotocore_iotwireless.literals import WirelessDeviceEventType
```

Values:

- `Downlink_Data`
- `Join`
- `Registration`
- `Rejoin`
- `Uplink_Data`

<a id="wirelessdeviceframeinfotype"></a>

## WirelessDeviceFrameInfoType

```python
from types_aiobotocore_iotwireless.literals import WirelessDeviceFrameInfoType
```

Values:

- `DISABLED`
- `ENABLED`

<a id="wirelessdeviceidtypetype"></a>

## WirelessDeviceIdTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessDeviceIdTypeType
```

Values:

- `DevEui`
- `SidewalkManufacturingSn`
- `ThingName`
- `WirelessDeviceId`

<a id="wirelessdevicetypetype"></a>

## WirelessDeviceTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessDeviceTypeType
```

Values:

- `LoRaWAN`
- `Sidewalk`

<a id="wirelessgatewayeventtype"></a>

## WirelessGatewayEventType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayEventType
```

Values:

- `Certificate`
- `CUPS_Request`

<a id="wirelessgatewayidtypetype"></a>

## WirelessGatewayIdTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayIdTypeType
```

Values:

- `GatewayEui`
- `ThingName`
- `WirelessGatewayId`

<a id="wirelessgatewayservicetypetype"></a>

## WirelessGatewayServiceTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayServiceTypeType
```

Values:

- `CUPS`
- `LNS`

<a id="wirelessgatewaytaskdefinitiontypetype"></a>

## WirelessGatewayTaskDefinitionTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayTaskDefinitionTypeType
```

Values:

- `UPDATE`

<a id="wirelessgatewaytaskstatustype"></a>

## WirelessGatewayTaskStatusType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayTaskStatusType
```

Values:

- `COMPLETED`
- `FAILED`
- `FIRST_RETRY`
- `IN_PROGRESS`
- `PENDING`
- `SECOND_RETRY`

<a id="wirelessgatewaytypetype"></a>

## WirelessGatewayTypeType

```python
from types_aiobotocore_iotwireless.literals import WirelessGatewayTypeType
```

Values:

- `LoRaWAN`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_iotwireless.literals import ServiceName
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
