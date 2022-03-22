<a id="literals-for-aiobotocore-amplify-module"></a>

# Literals for aiobotocore Amplify module

> [Index](../README.md) > [Amplify](./README.md) > Literals

Auto-generated documentation for
[Amplify](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplify.html#Amplify)
type annotations stubs module
[types-aiobotocore-amplify](https://pypi.org/project/types-aiobotocore-amplify/).

- [Literals for aiobotocore Amplify module](#literals-for-aiobotocore-amplify-module)
  - [DomainStatusType](#domainstatustype)
  - [JobStatusType](#jobstatustype)
  - [JobTypeType](#jobtypetype)
  - [ListAppsPaginatorName](#listappspaginatorname)
  - [ListBranchesPaginatorName](#listbranchespaginatorname)
  - [ListDomainAssociationsPaginatorName](#listdomainassociationspaginatorname)
  - [ListJobsPaginatorName](#listjobspaginatorname)
  - [PlatformType](#platformtype)
  - [RepositoryCloneMethodType](#repositoryclonemethodtype)
  - [StageType](#stagetype)
  - [AmplifyServiceName](#amplifyservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="domainstatustype"></a>

## DomainStatusType

```python
from types_aiobotocore_amplify.literals import DomainStatusType
```

Values:

- `AVAILABLE`
- `CREATING`
- `FAILED`
- `IN_PROGRESS`
- `PENDING_DEPLOYMENT`
- `PENDING_VERIFICATION`
- `REQUESTING_CERTIFICATE`
- `UPDATING`

<a id="jobstatustype"></a>

## JobStatusType

```python
from types_aiobotocore_amplify.literals import JobStatusType
```

Values:

- `CANCELLED`
- `CANCELLING`
- `FAILED`
- `PENDING`
- `PROVISIONING`
- `RUNNING`
- `SUCCEED`

<a id="jobtypetype"></a>

## JobTypeType

```python
from types_aiobotocore_amplify.literals import JobTypeType
```

Values:

- `MANUAL`
- `RELEASE`
- `RETRY`
- `WEB_HOOK`

<a id="listappspaginatorname"></a>

## ListAppsPaginatorName

```python
from types_aiobotocore_amplify.literals import ListAppsPaginatorName
```

Values:

- `list_apps`

<a id="listbranchespaginatorname"></a>

## ListBranchesPaginatorName

```python
from types_aiobotocore_amplify.literals import ListBranchesPaginatorName
```

Values:

- `list_branches`

<a id="listdomainassociationspaginatorname"></a>

## ListDomainAssociationsPaginatorName

```python
from types_aiobotocore_amplify.literals import ListDomainAssociationsPaginatorName
```

Values:

- `list_domain_associations`

<a id="listjobspaginatorname"></a>

## ListJobsPaginatorName

```python
from types_aiobotocore_amplify.literals import ListJobsPaginatorName
```

Values:

- `list_jobs`

<a id="platformtype"></a>

## PlatformType

```python
from types_aiobotocore_amplify.literals import PlatformType
```

Values:

- `WEB`
- `WEB_DYNAMIC`

<a id="repositoryclonemethodtype"></a>

## RepositoryCloneMethodType

```python
from types_aiobotocore_amplify.literals import RepositoryCloneMethodType
```

Values:

- `SIGV4`
- `SSH`
- `TOKEN`

<a id="stagetype"></a>

## StageType

```python
from types_aiobotocore_amplify.literals import StageType
```

Values:

- `BETA`
- `DEVELOPMENT`
- `EXPERIMENTAL`
- `PRODUCTION`
- `PULL_REQUEST`

<a id="amplifyservicename"></a>

## AmplifyServiceName

```python
from types_aiobotocore_amplify.literals import AmplifyServiceName
```

Values:

- `amplify`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_amplify.literals import ServiceName
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
from types_aiobotocore_amplify.literals import ResourceServiceName
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
from types_aiobotocore_amplify.literals import PaginatorName
```

Values:

- `list_apps`
- `list_branches`
- `list_domain_associations`
- `list_jobs`
