<a id="literals-for-aiobotocore-applicationautoscaling-module"></a>

# Literals for aiobotocore ApplicationAutoScaling module

> [Index](..) > [ApplicationAutoScaling](.) > Literals

Auto-generated documentation for
[ApplicationAutoScaling](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
type annotations stubs module
[types-aiobotocore-application-autoscaling](https://pypi.org/project/types-aiobotocore-application-autoscaling/).

- [Literals for aiobotocore ApplicationAutoScaling module](#literals-for-aiobotocore-applicationautoscaling-module)
  - [AdjustmentTypeType](#adjustmenttypetype)
  - [DescribeScalableTargetsPaginatorName](#describescalabletargetspaginatorname)
  - [DescribeScalingActivitiesPaginatorName](#describescalingactivitiespaginatorname)
  - [DescribeScalingPoliciesPaginatorName](#describescalingpoliciespaginatorname)
  - [DescribeScheduledActionsPaginatorName](#describescheduledactionspaginatorname)
  - [MetricAggregationTypeType](#metricaggregationtypetype)
  - [MetricStatisticType](#metricstatistictype)
  - [MetricTypeType](#metrictypetype)
  - [PolicyTypeType](#policytypetype)
  - [ScalableDimensionType](#scalabledimensiontype)
  - [ScalingActivityStatusCodeType](#scalingactivitystatuscodetype)
  - [ServiceNamespaceType](#servicenamespacetype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="adjustmenttypetype"></a>

## AdjustmentTypeType

```python
from types_aiobotocore_application_autoscaling.literals import AdjustmentTypeType
```

Values:

- `ChangeInCapacity`
- `ExactCapacity`
- `PercentChangeInCapacity`

<a id="describescalabletargetspaginatorname"></a>

## DescribeScalableTargetsPaginatorName

```python
from types_aiobotocore_application_autoscaling.literals import DescribeScalableTargetsPaginatorName
```

Values:

- `describe_scalable_targets`

<a id="describescalingactivitiespaginatorname"></a>

## DescribeScalingActivitiesPaginatorName

```python
from types_aiobotocore_application_autoscaling.literals import DescribeScalingActivitiesPaginatorName
```

Values:

- `describe_scaling_activities`

<a id="describescalingpoliciespaginatorname"></a>

## DescribeScalingPoliciesPaginatorName

```python
from types_aiobotocore_application_autoscaling.literals import DescribeScalingPoliciesPaginatorName
```

Values:

- `describe_scaling_policies`

<a id="describescheduledactionspaginatorname"></a>

## DescribeScheduledActionsPaginatorName

```python
from types_aiobotocore_application_autoscaling.literals import DescribeScheduledActionsPaginatorName
```

Values:

- `describe_scheduled_actions`

<a id="metricaggregationtypetype"></a>

## MetricAggregationTypeType

```python
from types_aiobotocore_application_autoscaling.literals import MetricAggregationTypeType
```

Values:

- `Average`
- `Maximum`
- `Minimum`

<a id="metricstatistictype"></a>

## MetricStatisticType

```python
from types_aiobotocore_application_autoscaling.literals import MetricStatisticType
```

Values:

- `Average`
- `Maximum`
- `Minimum`
- `SampleCount`
- `Sum`

<a id="metrictypetype"></a>

## MetricTypeType

```python
from types_aiobotocore_application_autoscaling.literals import MetricTypeType
```

Values:

- `ALBRequestCountPerTarget`
- `AppStreamAverageCapacityUtilization`
- `CassandraReadCapacityUtilization`
- `CassandraWriteCapacityUtilization`
- `ComprehendInferenceUtilization`
- `DynamoDBReadCapacityUtilization`
- `DynamoDBWriteCapacityUtilization`
- `EC2SpotFleetRequestAverageCPUUtilization`
- `EC2SpotFleetRequestAverageNetworkIn`
- `EC2SpotFleetRequestAverageNetworkOut`
- `ECSServiceAverageCPUUtilization`
- `ECSServiceAverageMemoryUtilization`
- `ElastiCacheDatabaseMemoryUsageCountedForEvictPercentage`
- `ElastiCachePrimaryEngineCPUUtilization`
- `ElastiCacheReplicaEngineCPUUtilization`
- `KafkaBrokerStorageUtilization`
- `LambdaProvisionedConcurrencyUtilization`
- `NeptuneReaderAverageCPUUtilization`
- `RDSReaderAverageCPUUtilization`
- `RDSReaderAverageDatabaseConnections`
- `SageMakerVariantInvocationsPerInstance`

<a id="policytypetype"></a>

## PolicyTypeType

```python
from types_aiobotocore_application_autoscaling.literals import PolicyTypeType
```

Values:

- `StepScaling`
- `TargetTrackingScaling`

<a id="scalabledimensiontype"></a>

## ScalableDimensionType

```python
from types_aiobotocore_application_autoscaling.literals import ScalableDimensionType
```

Values:

- `appstream:fleet:DesiredCapacity`
- `cassandra:table:ReadCapacityUnits`
- `cassandra:table:WriteCapacityUnits`
- `comprehend:document-classifier-endpoint:DesiredInferenceUnits`
- `comprehend:entity-recognizer-endpoint:DesiredInferenceUnits`
- `custom-resource:ResourceType:Property`
- `dynamodb:index:ReadCapacityUnits`
- `dynamodb:index:WriteCapacityUnits`
- `dynamodb:table:ReadCapacityUnits`
- `dynamodb:table:WriteCapacityUnits`
- `ec2:spot-fleet-request:TargetCapacity`
- `ecs:service:DesiredCount`
- `elasticache:replication-group:NodeGroups`
- `elasticache:replication-group:Replicas`
- `elasticmapreduce:instancegroup:InstanceCount`
- `kafka:broker-storage:VolumeSize`
- `lambda:function:ProvisionedConcurrency`
- `neptune:cluster:ReadReplicaCount`
- `rds:cluster:ReadReplicaCount`
- `sagemaker:variant:DesiredInstanceCount`

<a id="scalingactivitystatuscodetype"></a>

## ScalingActivityStatusCodeType

```python
from types_aiobotocore_application_autoscaling.literals import ScalingActivityStatusCodeType
```

Values:

- `Failed`
- `InProgress`
- `Overridden`
- `Pending`
- `Successful`
- `Unfulfilled`

<a id="servicenamespacetype"></a>

## ServiceNamespaceType

```python
from types_aiobotocore_application_autoscaling.literals import ServiceNamespaceType
```

Values:

- `appstream`
- `cassandra`
- `comprehend`
- `custom-resource`
- `dynamodb`
- `ec2`
- `ecs`
- `elasticache`
- `elasticmapreduce`
- `kafka`
- `lambda`
- `neptune`
- `rds`
- `sagemaker`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_application_autoscaling.literals import ServiceName
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
from types_aiobotocore_application_autoscaling.literals import PaginatorName
```

Values:

- `describe_scalable_targets`
- `describe_scaling_activities`
- `describe_scaling_policies`
- `describe_scheduled_actions`
