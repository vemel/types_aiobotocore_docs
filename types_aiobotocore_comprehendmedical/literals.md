<a id="literals-for-aiobotocore-comprehendmedical-module"></a>

# Literals for aiobotocore ComprehendMedical module

> [Index](..) > [ComprehendMedical](.) > Literals

Auto-generated documentation for
[ComprehendMedical](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
type annotations stubs module
[types-aiobotocore-comprehendmedical](https://pypi.org/project/types-aiobotocore-comprehendmedical/).

- [Literals for aiobotocore ComprehendMedical module](#literals-for-aiobotocore-comprehendmedical-module)
  - [AttributeNameType](#attributenametype)
  - [EntitySubTypeType](#entitysubtypetype)
  - [EntityTypeType](#entitytypetype)
  - [ICD10CMAttributeTypeType](#icd10cmattributetypetype)
  - [ICD10CMEntityCategoryType](#icd10cmentitycategorytype)
  - [ICD10CMEntityTypeType](#icd10cmentitytypetype)
  - [ICD10CMRelationshipTypeType](#icd10cmrelationshiptypetype)
  - [ICD10CMTraitNameType](#icd10cmtraitnametype)
  - [JobStatusType](#jobstatustype)
  - [LanguageCodeType](#languagecodetype)
  - [RelationshipTypeType](#relationshiptypetype)
  - [RxNormAttributeTypeType](#rxnormattributetypetype)
  - [RxNormEntityCategoryType](#rxnormentitycategorytype)
  - [RxNormEntityTypeType](#rxnormentitytypetype)
  - [RxNormTraitNameType](#rxnormtraitnametype)
  - [SNOMEDCTAttributeTypeType](#snomedctattributetypetype)
  - [SNOMEDCTEntityCategoryType](#snomedctentitycategorytype)
  - [SNOMEDCTEntityTypeType](#snomedctentitytypetype)
  - [SNOMEDCTRelationshipTypeType](#snomedctrelationshiptypetype)
  - [SNOMEDCTTraitNameType](#snomedcttraitnametype)
  - [ServiceName](#servicename)

<a id="attributenametype"></a>

## AttributeNameType

```python
from types_aiobotocore_comprehendmedical.literals import AttributeNameType
```

Values:

- `DIAGNOSIS`
- `NEGATION`
- `SIGN`
- `SYMPTOM`

<a id="entitysubtypetype"></a>

## EntitySubTypeType

```python
from types_aiobotocore_comprehendmedical.literals import EntitySubTypeType
```

Values:

- `ACUITY`
- `ADDRESS`
- `AGE`
- `BRAND_NAME`
- `CONTACT_POINT`
- `DATE`
- `DIRECTION`
- `DOSAGE`
- `DURATION`
- `DX_NAME`
- `EMAIL`
- `FORM`
- `FREQUENCY`
- `GENERIC_NAME`
- `ID`
- `IDENTIFIER`
- `NAME`
- `PHONE_OR_FAX`
- `PROCEDURE_NAME`
- `PROFESSION`
- `QUALITY`
- `QUANTITY`
- `RATE`
- `ROUTE_OR_MODE`
- `STRENGTH`
- `SYSTEM_ORGAN_SITE`
- `TEST_NAME`
- `TEST_UNIT`
- `TEST_UNITS`
- `TEST_VALUE`
- `TIME_EXPRESSION`
- `TIME_TO_DX_NAME`
- `TIME_TO_MEDICATION_NAME`
- `TIME_TO_PROCEDURE_NAME`
- `TIME_TO_TEST_NAME`
- `TIME_TO_TREATMENT_NAME`
- `TREATMENT_NAME`
- `URL`

<a id="entitytypetype"></a>

## EntityTypeType

```python
from types_aiobotocore_comprehendmedical.literals import EntityTypeType
```

Values:

- `ANATOMY`
- `MEDICAL_CONDITION`
- `MEDICATION`
- `PROTECTED_HEALTH_INFORMATION`
- `TEST_TREATMENT_PROCEDURE`
- `TIME_EXPRESSION`

<a id="icd10cmattributetypetype"></a>

## ICD10CMAttributeTypeType

```python
from types_aiobotocore_comprehendmedical.literals import ICD10CMAttributeTypeType
```

Values:

- `ACUITY`
- `DIRECTION`
- `QUALITY`
- `QUANTITY`
- `SYSTEM_ORGAN_SITE`
- `TIME_EXPRESSION`
- `TIME_TO_DX_NAME`

<a id="icd10cmentitycategorytype"></a>

## ICD10CMEntityCategoryType

```python
from types_aiobotocore_comprehendmedical.literals import ICD10CMEntityCategoryType
```

Values:

- `MEDICAL_CONDITION`

<a id="icd10cmentitytypetype"></a>

## ICD10CMEntityTypeType

```python
from types_aiobotocore_comprehendmedical.literals import ICD10CMEntityTypeType
```

Values:

- `DX_NAME`
- `TIME_EXPRESSION`

<a id="icd10cmrelationshiptypetype"></a>

## ICD10CMRelationshipTypeType

```python
from types_aiobotocore_comprehendmedical.literals import ICD10CMRelationshipTypeType
```

Values:

- `OVERLAP`
- `SYSTEM_ORGAN_SITE`

<a id="icd10cmtraitnametype"></a>

## ICD10CMTraitNameType

```python
from types_aiobotocore_comprehendmedical.literals import ICD10CMTraitNameType
```

Values:

- `DIAGNOSIS`
- `NEGATION`
- `SIGN`
- `SYMPTOM`

<a id="jobstatustype"></a>

## JobStatusType

```python
from types_aiobotocore_comprehendmedical.literals import JobStatusType
```

Values:

- `COMPLETED`
- `FAILED`
- `IN_PROGRESS`
- `PARTIAL_SUCCESS`
- `STOP_REQUESTED`
- `STOPPED`
- `SUBMITTED`

<a id="languagecodetype"></a>

## LanguageCodeType

```python
from types_aiobotocore_comprehendmedical.literals import LanguageCodeType
```

Values:

- `en`

<a id="relationshiptypetype"></a>

## RelationshipTypeType

```python
from types_aiobotocore_comprehendmedical.literals import RelationshipTypeType
```

Values:

- `ACUITY`
- `ADMINISTERED_VIA`
- `DIRECTION`
- `DOSAGE`
- `DURATION`
- `EVERY`
- `FOR`
- `FORM`
- `FREQUENCY`
- `NEGATIVE`
- `OVERLAP`
- `RATE`
- `ROUTE_OR_MODE`
- `STRENGTH`
- `SYSTEM_ORGAN_SITE`
- `TEST_UNIT`
- `TEST_UNITS`
- `TEST_VALUE`
- `WITH_DOSAGE`

<a id="rxnormattributetypetype"></a>

## RxNormAttributeTypeType

```python
from types_aiobotocore_comprehendmedical.literals import RxNormAttributeTypeType
```

Values:

- `DOSAGE`
- `DURATION`
- `FORM`
- `FREQUENCY`
- `RATE`
- `ROUTE_OR_MODE`
- `STRENGTH`

<a id="rxnormentitycategorytype"></a>

## RxNormEntityCategoryType

```python
from types_aiobotocore_comprehendmedical.literals import RxNormEntityCategoryType
```

Values:

- `MEDICATION`

<a id="rxnormentitytypetype"></a>

## RxNormEntityTypeType

```python
from types_aiobotocore_comprehendmedical.literals import RxNormEntityTypeType
```

Values:

- `BRAND_NAME`
- `GENERIC_NAME`

<a id="rxnormtraitnametype"></a>

## RxNormTraitNameType

```python
from types_aiobotocore_comprehendmedical.literals import RxNormTraitNameType
```

Values:

- `NEGATION`

<a id="snomedctattributetypetype"></a>

## SNOMEDCTAttributeTypeType

```python
from types_aiobotocore_comprehendmedical.literals import SNOMEDCTAttributeTypeType
```

Values:

- `ACUITY`
- `DIRECTION`
- `QUALITY`
- `SYSTEM_ORGAN_SITE`
- `TEST_UNIT`
- `TEST_VALUE`

<a id="snomedctentitycategorytype"></a>

## SNOMEDCTEntityCategoryType

```python
from types_aiobotocore_comprehendmedical.literals import SNOMEDCTEntityCategoryType
```

Values:

- `ANATOMY`
- `MEDICAL_CONDITION`
- `TEST_TREATMENT_PROCEDURE`

<a id="snomedctentitytypetype"></a>

## SNOMEDCTEntityTypeType

```python
from types_aiobotocore_comprehendmedical.literals import SNOMEDCTEntityTypeType
```

Values:

- `DX_NAME`
- `PROCEDURE_NAME`
- `TEST_NAME`
- `TREATMENT_NAME`

<a id="snomedctrelationshiptypetype"></a>

## SNOMEDCTRelationshipTypeType

```python
from types_aiobotocore_comprehendmedical.literals import SNOMEDCTRelationshipTypeType
```

Values:

- `ACUITY`
- `DIRECTION`
- `QUALITY`
- `SYSTEM_ORGAN_SITE`
- `TEST_UNITS`
- `TEST_VALUE`

<a id="snomedcttraitnametype"></a>

## SNOMEDCTTraitNameType

```python
from types_aiobotocore_comprehendmedical.literals import SNOMEDCTTraitNameType
```

Values:

- `DIAGNOSIS`
- `NEGATION`
- `SIGN`
- `SYMPTOM`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_comprehendmedical.literals import ServiceName
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
