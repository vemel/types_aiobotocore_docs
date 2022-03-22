<a id="literals-for-aiobotocore-cloudsearch-module"></a>

# Literals for aiobotocore CloudSearch module

> [Index](../README.md) > [CloudSearch](./README.md) > Literals

Auto-generated documentation for
[CloudSearch](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearch.html#CloudSearch)
type annotations stubs module
[types-aiobotocore-cloudsearch](https://pypi.org/project/types-aiobotocore-cloudsearch/).

- [Literals for aiobotocore CloudSearch module](#literals-for-aiobotocore-cloudsearch-module)
  - [AlgorithmicStemmingType](#algorithmicstemmingtype)
  - [AnalysisSchemeLanguageType](#analysisschemelanguagetype)
  - [IndexFieldTypeType](#indexfieldtypetype)
  - [OptionStateType](#optionstatetype)
  - [PartitionInstanceTypeType](#partitioninstancetypetype)
  - [SuggesterFuzzyMatchingType](#suggesterfuzzymatchingtype)
  - [TLSSecurityPolicyType](#tlssecuritypolicytype)
  - [CloudSearchServiceName](#cloudsearchservicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)

<a id="algorithmicstemmingtype"></a>

## AlgorithmicStemmingType

```python
from types_aiobotocore_cloudsearch.literals import AlgorithmicStemmingType
```

Values:

- `full`
- `light`
- `minimal`
- `none`

<a id="analysisschemelanguagetype"></a>

## AnalysisSchemeLanguageType

```python
from types_aiobotocore_cloudsearch.literals import AnalysisSchemeLanguageType
```

Values:

- `ar`
- `bg`
- `ca`
- `cs`
- `da`
- `de`
- `el`
- `en`
- `es`
- `eu`
- `fa`
- `fi`
- `fr`
- `ga`
- `gl`
- `he`
- `hi`
- `hu`
- `hy`
- `id`
- `it`
- `ja`
- `ko`
- `lv`
- `mul`
- `nl`
- `no`
- `pt`
- `ro`
- `ru`
- `sv`
- `th`
- `tr`
- `zh-Hans`
- `zh-Hant`

<a id="indexfieldtypetype"></a>

## IndexFieldTypeType

```python
from types_aiobotocore_cloudsearch.literals import IndexFieldTypeType
```

Values:

- `date`
- `date-array`
- `double`
- `double-array`
- `int`
- `int-array`
- `latlon`
- `literal`
- `literal-array`
- `text`
- `text-array`

<a id="optionstatetype"></a>

## OptionStateType

```python
from types_aiobotocore_cloudsearch.literals import OptionStateType
```

Values:

- `Active`
- `FailedToValidate`
- `Processing`
- `RequiresIndexDocuments`

<a id="partitioninstancetypetype"></a>

## PartitionInstanceTypeType

```python
from types_aiobotocore_cloudsearch.literals import PartitionInstanceTypeType
```

Values:

- `search.2xlarge`
- `search.large`
- `search.m1.large`
- `search.m1.small`
- `search.m2.2xlarge`
- `search.m2.xlarge`
- `search.m3.2xlarge`
- `search.m3.large`
- `search.m3.medium`
- `search.m3.xlarge`
- `search.medium`
- `search.previousgeneration.2xlarge`
- `search.previousgeneration.large`
- `search.previousgeneration.small`
- `search.previousgeneration.xlarge`
- `search.small`
- `search.xlarge`

<a id="suggesterfuzzymatchingtype"></a>

## SuggesterFuzzyMatchingType

```python
from types_aiobotocore_cloudsearch.literals import SuggesterFuzzyMatchingType
```

Values:

- `high`
- `low`
- `none`

<a id="tlssecuritypolicytype"></a>

## TLSSecurityPolicyType

```python
from types_aiobotocore_cloudsearch.literals import TLSSecurityPolicyType
```

Values:

- `Policy-Min-TLS-1-0-2019-07`
- `Policy-Min-TLS-1-2-2019-07`

<a id="cloudsearchservicename"></a>

## CloudSearchServiceName

```python
from types_aiobotocore_cloudsearch.literals import CloudSearchServiceName
```

Values:

- `cloudsearch`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_cloudsearch.literals import ServiceName
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
from types_aiobotocore_cloudsearch.literals import ResourceServiceName
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
