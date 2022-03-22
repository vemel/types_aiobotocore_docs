<a id="literals-for-aiobotocore-cloud9-module"></a>

# Literals for aiobotocore Cloud9 module

> [Index](../README.md) > [Cloud9](./README.md) > Literals

Auto-generated documentation for
[Cloud9](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
type annotations stubs module
[types-aiobotocore-cloud9](https://pypi.org/project/types-aiobotocore-cloud9/).

- [Literals for aiobotocore Cloud9 module](#literals-for-aiobotocore-cloud9-module)
  - [ConnectionTypeType](#connectiontypetype)
  - [DescribeEnvironmentMembershipsPaginatorName](#describeenvironmentmembershipspaginatorname)
  - [EnvironmentLifecycleStatusType](#environmentlifecyclestatustype)
  - [EnvironmentStatusType](#environmentstatustype)
  - [EnvironmentTypeType](#environmenttypetype)
  - [ListEnvironmentsPaginatorName](#listenvironmentspaginatorname)
  - [ManagedCredentialsActionType](#managedcredentialsactiontype)
  - [ManagedCredentialsStatusType](#managedcredentialsstatustype)
  - [MemberPermissionsType](#memberpermissionstype)
  - [PermissionsType](#permissionstype)
  - [Cloud9ServiceName](#cloud9servicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)
  - [PaginatorName](#paginatorname)

<a id="connectiontypetype"></a>

## ConnectionTypeType

```python
from types_aiobotocore_cloud9.literals import ConnectionTypeType
```

Values:

- `CONNECT_SSH`
- `CONNECT_SSM`

<a id="describeenvironmentmembershipspaginatorname"></a>

## DescribeEnvironmentMembershipsPaginatorName

```python
from types_aiobotocore_cloud9.literals import DescribeEnvironmentMembershipsPaginatorName
```

Values:

- `describe_environment_memberships`

<a id="environmentlifecyclestatustype"></a>

## EnvironmentLifecycleStatusType

```python
from types_aiobotocore_cloud9.literals import EnvironmentLifecycleStatusType
```

Values:

- `CREATE_FAILED`
- `CREATED`
- `CREATING`
- `DELETE_FAILED`
- `DELETING`

<a id="environmentstatustype"></a>

## EnvironmentStatusType

```python
from types_aiobotocore_cloud9.literals import EnvironmentStatusType
```

Values:

- `connecting`
- `creating`
- `deleting`
- `error`
- `ready`
- `stopped`
- `stopping`

<a id="environmenttypetype"></a>

## EnvironmentTypeType

```python
from types_aiobotocore_cloud9.literals import EnvironmentTypeType
```

Values:

- `ec2`
- `ssh`

<a id="listenvironmentspaginatorname"></a>

## ListEnvironmentsPaginatorName

```python
from types_aiobotocore_cloud9.literals import ListEnvironmentsPaginatorName
```

Values:

- `list_environments`

<a id="managedcredentialsactiontype"></a>

## ManagedCredentialsActionType

```python
from types_aiobotocore_cloud9.literals import ManagedCredentialsActionType
```

Values:

- `DISABLE`
- `ENABLE`

<a id="managedcredentialsstatustype"></a>

## ManagedCredentialsStatusType

```python
from types_aiobotocore_cloud9.literals import ManagedCredentialsStatusType
```

Values:

- `DISABLED_BY_COLLABORATOR`
- `DISABLED_BY_DEFAULT`
- `DISABLED_BY_OWNER`
- `ENABLED_BY_OWNER`
- `ENABLED_ON_CREATE`
- `FAILED_REMOVAL_BY_COLLABORATOR`
- `FAILED_REMOVAL_BY_OWNER`
- `PENDING_REMOVAL_BY_COLLABORATOR`
- `PENDING_REMOVAL_BY_OWNER`
- `PENDING_START_REMOVAL_BY_COLLABORATOR`
- `PENDING_START_REMOVAL_BY_OWNER`

<a id="memberpermissionstype"></a>

## MemberPermissionsType

```python
from types_aiobotocore_cloud9.literals import MemberPermissionsType
```

Values:

- `read-only`
- `read-write`

<a id="permissionstype"></a>

## PermissionsType

```python
from types_aiobotocore_cloud9.literals import PermissionsType
```

Values:

- `owner`
- `read-only`
- `read-write`

<a id="cloud9servicename"></a>

## Cloud9ServiceName

```python
from types_aiobotocore_cloud9.literals import Cloud9ServiceName
```

Values:

- `cloud9`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_cloud9.literals import ServiceName
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
from types_aiobotocore_cloud9.literals import ResourceServiceName
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
from types_aiobotocore_cloud9.literals import PaginatorName
```

Values:

- `describe_environment_memberships`
- `list_environments`
