<a id="literals-for-aiobotocore-autoscalingplans-module"></a>

# Literals for aiobotocore AutoScalingPlans module

> [Index](..) > [AutoScalingPlans](.) > Literals

Auto-generated documentation for
[AutoScalingPlans](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
type annotations stubs module
[types-aiobotocore-autoscaling-plans](https://pypi.org/project/types-aiobotocore-autoscaling-plans/).

- [Literals for aiobotocore AutoScalingPlans module](#literals-for-aiobotocore-autoscalingplans-module)
  - [DescribeScalingPlanResourcesPaginatorName](#describescalingplanresourcespaginatorname)
  - [DescribeScalingPlansPaginatorName](#describescalingplanspaginatorname)
  - [ForecastDataTypeType](#forecastdatatypetype)
  - [LoadMetricTypeType](#loadmetrictypetype)
  - [MetricStatisticType](#metricstatistictype)
  - [PolicyTypeType](#policytypetype)
  - [PredictiveScalingMaxCapacityBehaviorType](#predictivescalingmaxcapacitybehaviortype)
  - [PredictiveScalingModeType](#predictivescalingmodetype)
  - [ScalableDimensionType](#scalabledimensiontype)
  - [ScalingMetricTypeType](#scalingmetrictypetype)
  - [ScalingPlanStatusCodeType](#scalingplanstatuscodetype)
  - [ScalingPolicyUpdateBehaviorType](#scalingpolicyupdatebehaviortype)
  - [ScalingStatusCodeType](#scalingstatuscodetype)
  - [ServiceNamespaceType](#servicenamespacetype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="describescalingplanresourcespaginatorname"></a>

## DescribeScalingPlanResourcesPaginatorName

```python
from types_aiobotocore_autoscaling_plans.literals import DescribeScalingPlanResourcesPaginatorName
```

Values:

- `describe_scaling_plan_resources`

<a id="describescalingplanspaginatorname"></a>

## DescribeScalingPlansPaginatorName

```python
from types_aiobotocore_autoscaling_plans.literals import DescribeScalingPlansPaginatorName
```

Values:

- `describe_scaling_plans`

<a id="forecastdatatypetype"></a>

## ForecastDataTypeType

```python
from types_aiobotocore_autoscaling_plans.literals import ForecastDataTypeType
```

Values:

- `CapacityForecast`
- `LoadForecast`
- `ScheduledActionMaxCapacity`
- `ScheduledActionMinCapacity`

<a id="loadmetrictypetype"></a>

## LoadMetricTypeType

```python
from types_aiobotocore_autoscaling_plans.literals import LoadMetricTypeType
```

Values:

- `ALBTargetGroupRequestCount`
- `ASGTotalCPUUtilization`
- `ASGTotalNetworkIn`
- `ASGTotalNetworkOut`

<a id="metricstatistictype"></a>

## MetricStatisticType

```python
from types_aiobotocore_autoscaling_plans.literals import MetricStatisticType
```

Values:

- `Average`
- `Maximum`
- `Minimum`
- `SampleCount`
- `Sum`

<a id="policytypetype"></a>

## PolicyTypeType

```python
from types_aiobotocore_autoscaling_plans.literals import PolicyTypeType
```

Values:

- `TargetTrackingScaling`

<a id="predictivescalingmaxcapacitybehaviortype"></a>

## PredictiveScalingMaxCapacityBehaviorType

```python
from types_aiobotocore_autoscaling_plans.literals import PredictiveScalingMaxCapacityBehaviorType
```

Values:

- `SetForecastCapacityToMaxCapacity`
- `SetMaxCapacityAboveForecastCapacity`
- `SetMaxCapacityToForecastCapacity`

<a id="predictivescalingmodetype"></a>

## PredictiveScalingModeType

```python
from types_aiobotocore_autoscaling_plans.literals import PredictiveScalingModeType
```

Values:

- `ForecastAndScale`
- `ForecastOnly`

<a id="scalabledimensiontype"></a>

## ScalableDimensionType

```python
from types_aiobotocore_autoscaling_plans.literals import ScalableDimensionType
```

Values:

- `autoscaling:autoScalingGroup:DesiredCapacity`
- `dynamodb:index:ReadCapacityUnits`
- `dynamodb:index:WriteCapacityUnits`
- `dynamodb:table:ReadCapacityUnits`
- `dynamodb:table:WriteCapacityUnits`
- `ec2:spot-fleet-request:TargetCapacity`
- `ecs:service:DesiredCount`
- `rds:cluster:ReadReplicaCount`

<a id="scalingmetrictypetype"></a>

## ScalingMetricTypeType

```python
from types_aiobotocore_autoscaling_plans.literals import ScalingMetricTypeType
```

Values:

- `ALBRequestCountPerTarget`
- `ASGAverageCPUUtilization`
- `ASGAverageNetworkIn`
- `ASGAverageNetworkOut`
- `DynamoDBReadCapacityUtilization`
- `DynamoDBWriteCapacityUtilization`
- `EC2SpotFleetRequestAverageCPUUtilization`
- `EC2SpotFleetRequestAverageNetworkIn`
- `EC2SpotFleetRequestAverageNetworkOut`
- `ECSServiceAverageCPUUtilization`
- `ECSServiceAverageMemoryUtilization`
- `RDSReaderAverageCPUUtilization`
- `RDSReaderAverageDatabaseConnections`

<a id="scalingplanstatuscodetype"></a>

## ScalingPlanStatusCodeType

```python
from types_aiobotocore_autoscaling_plans.literals import ScalingPlanStatusCodeType
```

Values:

- `Active`
- `ActiveWithProblems`
- `CreationFailed`
- `CreationInProgress`
- `DeletionFailed`
- `DeletionInProgress`
- `UpdateFailed`
- `UpdateInProgress`

<a id="scalingpolicyupdatebehaviortype"></a>

## ScalingPolicyUpdateBehaviorType

```python
from types_aiobotocore_autoscaling_plans.literals import ScalingPolicyUpdateBehaviorType
```

Values:

- `KeepExternalPolicies`
- `ReplaceExternalPolicies`

<a id="scalingstatuscodetype"></a>

## ScalingStatusCodeType

```python
from types_aiobotocore_autoscaling_plans.literals import ScalingStatusCodeType
```

Values:

- `Active`
- `Inactive`
- `PartiallyActive`

<a id="servicenamespacetype"></a>

## ServiceNamespaceType

```python
from types_aiobotocore_autoscaling_plans.literals import ServiceNamespaceType
```

Values:

- `autoscaling`
- `dynamodb`
- `ec2`
- `ecs`
- `rds`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_autoscaling_plans.literals import ServiceName
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
from types_aiobotocore_autoscaling_plans.literals import PaginatorName
```

Values:

- `describe_scaling_plan_resources`
- `describe_scaling_plans`
