<a id="literals-for-aiobotocore-signer-module"></a>

# Literals for aiobotocore signer module

> [Index](..) > [signer](.) > Literals

Auto-generated documentation for
[signer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
type annotations stubs module
[types-aiobotocore-signer](https://pypi.org/project/types-aiobotocore-signer/).

- [Literals for aiobotocore signer module](#literals-for-aiobotocore-signer-module)
  - [CategoryType](#categorytype)
  - [EncryptionAlgorithmType](#encryptionalgorithmtype)
  - [HashAlgorithmType](#hashalgorithmtype)
  - [ImageFormatType](#imageformattype)
  - [ListSigningJobsPaginatorName](#listsigningjobspaginatorname)
  - [ListSigningPlatformsPaginatorName](#listsigningplatformspaginatorname)
  - [ListSigningProfilesPaginatorName](#listsigningprofilespaginatorname)
  - [SigningProfileStatusType](#signingprofilestatustype)
  - [SigningStatusType](#signingstatustype)
  - [SuccessfulSigningJobWaiterName](#successfulsigningjobwaitername)
  - [ValidityTypeType](#validitytypetype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)
  - [WaiterName](#waitername)

<a id="categorytype"></a>

## CategoryType

```python
from types_aiobotocore_signer.literals import CategoryType
```

Values:

- `AWSIoT`

<a id="encryptionalgorithmtype"></a>

## EncryptionAlgorithmType

```python
from types_aiobotocore_signer.literals import EncryptionAlgorithmType
```

Values:

- `ECDSA`
- `RSA`

<a id="hashalgorithmtype"></a>

## HashAlgorithmType

```python
from types_aiobotocore_signer.literals import HashAlgorithmType
```

Values:

- `SHA1`
- `SHA256`

<a id="imageformattype"></a>

## ImageFormatType

```python
from types_aiobotocore_signer.literals import ImageFormatType
```

Values:

- `JSON`
- `JSONDetached`
- `JSONEmbedded`

<a id="listsigningjobspaginatorname"></a>

## ListSigningJobsPaginatorName

```python
from types_aiobotocore_signer.literals import ListSigningJobsPaginatorName
```

Values:

- `list_signing_jobs`

<a id="listsigningplatformspaginatorname"></a>

## ListSigningPlatformsPaginatorName

```python
from types_aiobotocore_signer.literals import ListSigningPlatformsPaginatorName
```

Values:

- `list_signing_platforms`

<a id="listsigningprofilespaginatorname"></a>

## ListSigningProfilesPaginatorName

```python
from types_aiobotocore_signer.literals import ListSigningProfilesPaginatorName
```

Values:

- `list_signing_profiles`

<a id="signingprofilestatustype"></a>

## SigningProfileStatusType

```python
from types_aiobotocore_signer.literals import SigningProfileStatusType
```

Values:

- `Active`
- `Canceled`
- `Revoked`

<a id="signingstatustype"></a>

## SigningStatusType

```python
from types_aiobotocore_signer.literals import SigningStatusType
```

Values:

- `Failed`
- `InProgress`
- `Succeeded`

<a id="successfulsigningjobwaitername"></a>

## SuccessfulSigningJobWaiterName

```python
from types_aiobotocore_signer.literals import SuccessfulSigningJobWaiterName
```

Values:

- `successful_signing_job`

<a id="validitytypetype"></a>

## ValidityTypeType

```python
from types_aiobotocore_signer.literals import ValidityTypeType
```

Values:

- `DAYS`
- `MONTHS`
- `YEARS`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_signer.literals import ServiceName
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
from types_aiobotocore_signer.literals import PaginatorName
```

Values:

- `list_signing_jobs`
- `list_signing_platforms`
- `list_signing_profiles`

<a id="waitername"></a>

## WaiterName

```python
from types_aiobotocore_signer.literals import WaiterName
```

Values:

- `successful_signing_job`
