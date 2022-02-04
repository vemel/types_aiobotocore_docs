<a id="literals-for-aiobotocore-managedgrafana-module"></a>

# Literals for aiobotocore ManagedGrafana module

> [Index](..) > [ManagedGrafana](.) > Literals

Auto-generated documentation for
[ManagedGrafana](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/grafana.html#ManagedGrafana)
type annotations stubs module
[types-aiobotocore-grafana](https://pypi.org/project/types-aiobotocore-grafana/).

- [Literals for aiobotocore ManagedGrafana module](#literals-for-aiobotocore-managedgrafana-module)
  - [AccountAccessTypeType](#accountaccesstypetype)
  - [AuthenticationProviderTypesType](#authenticationprovidertypestype)
  - [DataSourceTypeType](#datasourcetypetype)
  - [LicenseTypeType](#licensetypetype)
  - [ListPermissionsPaginatorName](#listpermissionspaginatorname)
  - [ListWorkspacesPaginatorName](#listworkspacespaginatorname)
  - [NotificationDestinationTypeType](#notificationdestinationtypetype)
  - [PermissionTypeType](#permissiontypetype)
  - [RoleType](#roletype)
  - [SamlConfigurationStatusType](#samlconfigurationstatustype)
  - [UpdateActionType](#updateactiontype)
  - [UserTypeType](#usertypetype)
  - [WorkspaceStatusType](#workspacestatustype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="accountaccesstypetype"></a>

## AccountAccessTypeType

```python
from types_aiobotocore_grafana.literals import AccountAccessTypeType
```

Values:

- `CURRENT_ACCOUNT`
- `ORGANIZATION`

<a id="authenticationprovidertypestype"></a>

## AuthenticationProviderTypesType

```python
from types_aiobotocore_grafana.literals import AuthenticationProviderTypesType
```

Values:

- `AWS_SSO`
- `SAML`

<a id="datasourcetypetype"></a>

## DataSourceTypeType

```python
from types_aiobotocore_grafana.literals import DataSourceTypeType
```

Values:

- `AMAZON_OPENSEARCH_SERVICE`
- `CLOUDWATCH`
- `PROMETHEUS`
- `SITEWISE`
- `TIMESTREAM`
- `XRAY`

<a id="licensetypetype"></a>

## LicenseTypeType

```python
from types_aiobotocore_grafana.literals import LicenseTypeType
```

Values:

- `ENTERPRISE`
- `ENTERPRISE_FREE_TRIAL`

<a id="listpermissionspaginatorname"></a>

## ListPermissionsPaginatorName

```python
from types_aiobotocore_grafana.literals import ListPermissionsPaginatorName
```

Values:

- `list_permissions`

<a id="listworkspacespaginatorname"></a>

## ListWorkspacesPaginatorName

```python
from types_aiobotocore_grafana.literals import ListWorkspacesPaginatorName
```

Values:

- `list_workspaces`

<a id="notificationdestinationtypetype"></a>

## NotificationDestinationTypeType

```python
from types_aiobotocore_grafana.literals import NotificationDestinationTypeType
```

Values:

- `SNS`

<a id="permissiontypetype"></a>

## PermissionTypeType

```python
from types_aiobotocore_grafana.literals import PermissionTypeType
```

Values:

- `CUSTOMER_MANAGED`
- `SERVICE_MANAGED`

<a id="roletype"></a>

## RoleType

```python
from types_aiobotocore_grafana.literals import RoleType
```

Values:

- `ADMIN`
- `EDITOR`

<a id="samlconfigurationstatustype"></a>

## SamlConfigurationStatusType

```python
from types_aiobotocore_grafana.literals import SamlConfigurationStatusType
```

Values:

- `CONFIGURED`
- `NOT_CONFIGURED`

<a id="updateactiontype"></a>

## UpdateActionType

```python
from types_aiobotocore_grafana.literals import UpdateActionType
```

Values:

- `ADD`
- `REVOKE`

<a id="usertypetype"></a>

## UserTypeType

```python
from types_aiobotocore_grafana.literals import UserTypeType
```

Values:

- `SSO_GROUP`
- `SSO_USER`

<a id="workspacestatustype"></a>

## WorkspaceStatusType

```python
from types_aiobotocore_grafana.literals import WorkspaceStatusType
```

Values:

- `ACTIVE`
- `CREATING`
- `CREATION_FAILED`
- `DELETING`
- `DELETION_FAILED`
- `FAILED`
- `LICENSE_REMOVAL_FAILED`
- `UPDATE_FAILED`
- `UPDATING`
- `UPGRADE_FAILED`
- `UPGRADING`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_grafana.literals import ServiceName
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
from types_aiobotocore_grafana.literals import PaginatorName
```

Values:

- `list_permissions`
- `list_workspaces`
