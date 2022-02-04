<a id="literals-for-aiobotocore-transfer-module"></a>

# Literals for aiobotocore Transfer module

> [Index](..) > [Transfer](.) > Literals

Auto-generated documentation for
[Transfer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transfer.html#Transfer)
type annotations stubs module
[types-aiobotocore-transfer](https://pypi.org/project/types-aiobotocore-transfer/).

- [Literals for aiobotocore Transfer module](#literals-for-aiobotocore-transfer-module)
  - [CustomStepStatusType](#customstepstatustype)
  - [DomainType](#domaintype)
  - [EndpointTypeType](#endpointtypetype)
  - [ExecutionErrorTypeType](#executionerrortypetype)
  - [ExecutionStatusType](#executionstatustype)
  - [HomeDirectoryTypeType](#homedirectorytypetype)
  - [IdentityProviderTypeType](#identityprovidertypetype)
  - [ListServersPaginatorName](#listserverspaginatorname)
  - [OverwriteExistingType](#overwriteexistingtype)
  - [ProtocolType](#protocoltype)
  - [StateType](#statetype)
  - [WorkflowStepTypeType](#workflowsteptypetype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="customstepstatustype"></a>

## CustomStepStatusType

```python
from types_aiobotocore_transfer.literals import CustomStepStatusType
```

Values:

- `FAILURE`
- `SUCCESS`

<a id="domaintype"></a>

## DomainType

```python
from types_aiobotocore_transfer.literals import DomainType
```

Values:

- `EFS`
- `S3`

<a id="endpointtypetype"></a>

## EndpointTypeType

```python
from types_aiobotocore_transfer.literals import EndpointTypeType
```

Values:

- `PUBLIC`
- `VPC`
- `VPC_ENDPOINT`

<a id="executionerrortypetype"></a>

## ExecutionErrorTypeType

```python
from types_aiobotocore_transfer.literals import ExecutionErrorTypeType
```

Values:

- `PERMISSION_DENIED`

<a id="executionstatustype"></a>

## ExecutionStatusType

```python
from types_aiobotocore_transfer.literals import ExecutionStatusType
```

Values:

- `COMPLETED`
- `EXCEPTION`
- `HANDLING_EXCEPTION`
- `IN_PROGRESS`

<a id="homedirectorytypetype"></a>

## HomeDirectoryTypeType

```python
from types_aiobotocore_transfer.literals import HomeDirectoryTypeType
```

Values:

- `LOGICAL`
- `PATH`

<a id="identityprovidertypetype"></a>

## IdentityProviderTypeType

```python
from types_aiobotocore_transfer.literals import IdentityProviderTypeType
```

Values:

- `API_GATEWAY`
- `AWS_DIRECTORY_SERVICE`
- `AWS_LAMBDA`
- `SERVICE_MANAGED`

<a id="listserverspaginatorname"></a>

## ListServersPaginatorName

```python
from types_aiobotocore_transfer.literals import ListServersPaginatorName
```

Values:

- `list_servers`

<a id="overwriteexistingtype"></a>

## OverwriteExistingType

```python
from types_aiobotocore_transfer.literals import OverwriteExistingType
```

Values:

- `FALSE`
- `TRUE`

<a id="protocoltype"></a>

## ProtocolType

```python
from types_aiobotocore_transfer.literals import ProtocolType
```

Values:

- `FTP`
- `FTPS`
- `SFTP`

<a id="statetype"></a>

## StateType

```python
from types_aiobotocore_transfer.literals import StateType
```

Values:

- `OFFLINE`
- `ONLINE`
- `START_FAILED`
- `STARTING`
- `STOP_FAILED`
- `STOPPING`

<a id="workflowsteptypetype"></a>

## WorkflowStepTypeType

```python
from types_aiobotocore_transfer.literals import WorkflowStepTypeType
```

Values:

- `COPY`
- `CUSTOM`
- `DELETE`
- `TAG`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_transfer.literals import ServiceName
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
from types_aiobotocore_transfer.literals import PaginatorName
```

Values:

- `list_servers`
