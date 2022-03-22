<a id="literals-for-aiobotocore-apprunner-module"></a>

# Literals for aiobotocore AppRunner module

> [Index](../README.md) > [AppRunner](./README.md) > Literals

Auto-generated documentation for
[AppRunner](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
type annotations stubs module
[types-aiobotocore-apprunner](https://pypi.org/project/types-aiobotocore-apprunner/).

- [Literals for aiobotocore AppRunner module](#literals-for-aiobotocore-apprunner-module)
  - [AutoScalingConfigurationStatusType](#autoscalingconfigurationstatustype)
  - [CertificateValidationRecordStatusType](#certificatevalidationrecordstatustype)
  - [ConfigurationSourceType](#configurationsourcetype)
  - [ConnectionStatusType](#connectionstatustype)
  - [CustomDomainAssociationStatusType](#customdomainassociationstatustype)
  - [EgressTypeType](#egresstypetype)
  - [HealthCheckProtocolType](#healthcheckprotocoltype)
  - [ImageRepositoryTypeType](#imagerepositorytypetype)
  - [OperationStatusType](#operationstatustype)
  - [OperationTypeType](#operationtypetype)
  - [ProviderTypeType](#providertypetype)
  - [RuntimeType](#runtimetype)
  - [ServiceStatusType](#servicestatustype)
  - [SourceCodeVersionTypeType](#sourcecodeversiontypetype)
  - [VpcConnectorStatusType](#vpcconnectorstatustype)
  - [AppRunnerServiceName](#apprunnerservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)

<a id="autoscalingconfigurationstatustype"></a>

## AutoScalingConfigurationStatusType

```python
from types_aiobotocore_apprunner.literals import AutoScalingConfigurationStatusType
```

Values:

- `ACTIVE`
- `INACTIVE`

<a id="certificatevalidationrecordstatustype"></a>

## CertificateValidationRecordStatusType

```python
from types_aiobotocore_apprunner.literals import CertificateValidationRecordStatusType
```

Values:

- `FAILED`
- `PENDING_VALIDATION`
- `SUCCESS`

<a id="configurationsourcetype"></a>

## ConfigurationSourceType

```python
from types_aiobotocore_apprunner.literals import ConfigurationSourceType
```

Values:

- `API`
- `REPOSITORY`

<a id="connectionstatustype"></a>

## ConnectionStatusType

```python
from types_aiobotocore_apprunner.literals import ConnectionStatusType
```

Values:

- `AVAILABLE`
- `DELETED`
- `ERROR`
- `PENDING_HANDSHAKE`

<a id="customdomainassociationstatustype"></a>

## CustomDomainAssociationStatusType

```python
from types_aiobotocore_apprunner.literals import CustomDomainAssociationStatusType
```

Values:

- `ACTIVE`
- `BINDING_CERTIFICATE`
- `CREATE_FAILED`
- `CREATING`
- `DELETE_FAILED`
- `DELETING`
- `PENDING_CERTIFICATE_DNS_VALIDATION`

<a id="egresstypetype"></a>

## EgressTypeType

```python
from types_aiobotocore_apprunner.literals import EgressTypeType
```

Values:

- `DEFAULT`
- `VPC`

<a id="healthcheckprotocoltype"></a>

## HealthCheckProtocolType

```python
from types_aiobotocore_apprunner.literals import HealthCheckProtocolType
```

Values:

- `HTTP`
- `TCP`

<a id="imagerepositorytypetype"></a>

## ImageRepositoryTypeType

```python
from types_aiobotocore_apprunner.literals import ImageRepositoryTypeType
```

Values:

- `ECR`
- `ECR_PUBLIC`

<a id="operationstatustype"></a>

## OperationStatusType

```python
from types_aiobotocore_apprunner.literals import OperationStatusType
```

Values:

- `FAILED`
- `IN_PROGRESS`
- `PENDING`
- `ROLLBACK_FAILED`
- `ROLLBACK_IN_PROGRESS`
- `ROLLBACK_SUCCEEDED`
- `SUCCEEDED`

<a id="operationtypetype"></a>

## OperationTypeType

```python
from types_aiobotocore_apprunner.literals import OperationTypeType
```

Values:

- `CREATE_SERVICE`
- `DELETE_SERVICE`
- `PAUSE_SERVICE`
- `RESUME_SERVICE`
- `START_DEPLOYMENT`

<a id="providertypetype"></a>

## ProviderTypeType

```python
from types_aiobotocore_apprunner.literals import ProviderTypeType
```

Values:

- `GITHUB`

<a id="runtimetype"></a>

## RuntimeType

```python
from types_aiobotocore_apprunner.literals import RuntimeType
```

Values:

- `CORRETTO_11`
- `CORRETTO_8`
- `NODEJS_12`
- `NODEJS_14`
- `PYTHON_3`

<a id="servicestatustype"></a>

## ServiceStatusType

```python
from types_aiobotocore_apprunner.literals import ServiceStatusType
```

Values:

- `CREATE_FAILED`
- `DELETE_FAILED`
- `DELETED`
- `OPERATION_IN_PROGRESS`
- `PAUSED`
- `RUNNING`

<a id="sourcecodeversiontypetype"></a>

## SourceCodeVersionTypeType

```python
from types_aiobotocore_apprunner.literals import SourceCodeVersionTypeType
```

Values:

- `BRANCH`

<a id="vpcconnectorstatustype"></a>

## VpcConnectorStatusType

```python
from types_aiobotocore_apprunner.literals import VpcConnectorStatusType
```

Values:

- `ACTIVE`
- `INACTIVE`

<a id="apprunnerservicename"></a>

## AppRunnerServiceName

```python
from types_aiobotocore_apprunner.literals import AppRunnerServiceName
```

Values:

- `apprunner`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_apprunner.literals import ServiceName
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
from types_aiobotocore_apprunner.literals import ResourceServiceName
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
