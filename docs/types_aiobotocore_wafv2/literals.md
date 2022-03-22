<a id="literals-for-aiobotocore-wafv2-module"></a>

# Literals for aiobotocore WAFV2 module

> [Index](../README.md) > [WAFV2](./README.md) > Literals

Auto-generated documentation for
[WAFV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wafv2.html#WAFV2)
type annotations stubs module
[types-aiobotocore-wafv2](https://pypi.org/project/types-aiobotocore-wafv2/).

- [Literals for aiobotocore WAFV2 module](#literals-for-aiobotocore-wafv2-module)
  - [ActionValueType](#actionvaluetype)
  - [BodyParsingFallbackBehaviorType](#bodyparsingfallbackbehaviortype)
  - [ComparisonOperatorType](#comparisonoperatortype)
  - [CountryCodeType](#countrycodetype)
  - [FailureReasonType](#failurereasontype)
  - [FallbackBehaviorType](#fallbackbehaviortype)
  - [FilterBehaviorType](#filterbehaviortype)
  - [FilterRequirementType](#filterrequirementtype)
  - [ForwardedIPPositionType](#forwardedippositiontype)
  - [IPAddressVersionType](#ipaddressversiontype)
  - [JsonMatchScopeType](#jsonmatchscopetype)
  - [LabelMatchScopeType](#labelmatchscopetype)
  - [PayloadTypeType](#payloadtypetype)
  - [PlatformType](#platformtype)
  - [PositionalConstraintType](#positionalconstrainttype)
  - [RateBasedStatementAggregateKeyTypeType](#ratebasedstatementaggregatekeytypetype)
  - [ResourceTypeType](#resourcetypetype)
  - [ResponseContentTypeType](#responsecontenttypetype)
  - [ScopeType](#scopetype)
  - [TextTransformationTypeType](#texttransformationtypetype)
  - [WAFV2ServiceName](#wafv2servicename)
  - [ServiceName](#servicename)
  - [ResourceServiceName](#resourceservicename)

<a id="actionvaluetype"></a>

## ActionValueType

```python
from types_aiobotocore_wafv2.literals import ActionValueType
```

Values:

- `ALLOW`
- `BLOCK`
- `CAPTCHA`
- `COUNT`
- `EXCLUDED_AS_COUNT`

<a id="bodyparsingfallbackbehaviortype"></a>

## BodyParsingFallbackBehaviorType

```python
from types_aiobotocore_wafv2.literals import BodyParsingFallbackBehaviorType
```

Values:

- `EVALUATE_AS_STRING`
- `MATCH`
- `NO_MATCH`

<a id="comparisonoperatortype"></a>

## ComparisonOperatorType

```python
from types_aiobotocore_wafv2.literals import ComparisonOperatorType
```

Values:

- `EQ`
- `GE`
- `GT`
- `LE`
- `LT`
- `NE`

<a id="countrycodetype"></a>

## CountryCodeType

```python
from types_aiobotocore_wafv2.literals import CountryCodeType
```

Values:

- `AD`
- `AE`
- `AF`
- `AG`
- `AI`
- `AL`
- `AM`
- `AO`
- `AQ`
- `AR`
- `AS`
- `AT`
- `AU`
- `AW`
- `AX`
- `AZ`
- `BA`
- `BB`
- `BD`
- `BE`
- `BF`
- `BG`
- `BH`
- `BI`
- `BJ`
- `BL`
- `BM`
- `BN`
- `BO`
- `BQ`
- `BR`
- `BS`
- `BT`
- `BV`
- `BW`
- `BY`
- `BZ`
- `CA`
- `CC`
- `CD`
- `CF`
- `CG`
- `CH`
- `CI`
- `CK`
- `CL`
- `CM`
- `CN`
- `CO`
- `CR`
- `CU`
- `CV`
- `CW`
- `CX`
- `CY`
- `CZ`
- `DE`
- `DJ`
- `DK`
- `DM`
- `DO`
- `DZ`
- `EC`
- `EE`
- `EG`
- `EH`
- `ER`
- `ES`
- `ET`
- `FI`
- `FJ`
- `FK`
- `FM`
- `FO`
- `FR`
- `GA`
- `GB`
- `GD`
- `GE`
- `GF`
- `GG`
- `GH`
- `GI`
- `GL`
- `GM`
- `GN`
- `GP`
- `GQ`
- `GR`
- `GS`
- `GT`
- `GU`
- `GW`
- `GY`
- `HK`
- `HM`
- `HN`
- `HR`
- `HT`
- `HU`
- `ID`
- `IE`
- `IL`
- `IM`
- `IN`
- `IO`
- `IQ`
- `IR`
- `IS`
- `IT`
- `JE`
- `JM`
- `JO`
- `JP`
- `KE`
- `KG`
- `KH`
- `KI`
- `KM`
- `KN`
- `KP`
- `KR`
- `KW`
- `KY`
- `KZ`
- `LA`
- `LB`
- `LC`
- `LI`
- `LK`
- `LR`
- `LS`
- `LT`
- `LU`
- `LV`
- `LY`
- `MA`
- `MC`
- `MD`
- `ME`
- `MF`
- `MG`
- `MH`
- `MK`
- `ML`
- `MM`
- `MN`
- `MO`
- `MP`
- `MQ`
- `MR`
- `MS`
- `MT`
- `MU`
- `MV`
- `MW`
- `MX`
- `MY`
- `MZ`
- `NA`
- `NC`
- `NE`
- `NF`
- `NG`
- `NI`
- `NL`
- `NO`
- `NP`
- `NR`
- `NU`
- `NZ`
- `OM`
- `PA`
- `PE`
- `PF`
- `PG`
- `PH`
- `PK`
- `PL`
- `PM`
- `PN`
- `PR`
- `PS`
- `PT`
- `PW`
- `PY`
- `QA`
- `RE`
- `RO`
- `RS`
- `RU`
- `RW`
- `SA`
- `SB`
- `SC`
- `SD`
- `SE`
- `SG`
- `SH`
- `SI`
- `SJ`
- `SK`
- `SL`
- `SM`
- `SN`
- `SO`
- `SR`
- `SS`
- `ST`
- `SV`
- `SX`
- `SY`
- `SZ`
- `TC`
- `TD`
- `TF`
- `TG`
- `TH`
- `TJ`
- `TK`
- `TL`
- `TM`
- `TN`
- `TO`
- `TR`
- `TT`
- `TV`
- `TW`
- `TZ`
- `UA`
- `UG`
- `UM`
- `US`
- `UY`
- `UZ`
- `VA`
- `VC`
- `VE`
- `VG`
- `VI`
- `VN`
- `VU`
- `WF`
- `WS`
- `YE`
- `YT`
- `ZA`
- `ZM`
- `ZW`

<a id="failurereasontype"></a>

## FailureReasonType

```python
from types_aiobotocore_wafv2.literals import FailureReasonType
```

Values:

- `TOKEN_EXPIRED`
- `TOKEN_MISSING`

<a id="fallbackbehaviortype"></a>

## FallbackBehaviorType

```python
from types_aiobotocore_wafv2.literals import FallbackBehaviorType
```

Values:

- `MATCH`
- `NO_MATCH`

<a id="filterbehaviortype"></a>

## FilterBehaviorType

```python
from types_aiobotocore_wafv2.literals import FilterBehaviorType
```

Values:

- `DROP`
- `KEEP`

<a id="filterrequirementtype"></a>

## FilterRequirementType

```python
from types_aiobotocore_wafv2.literals import FilterRequirementType
```

Values:

- `MEETS_ALL`
- `MEETS_ANY`

<a id="forwardedippositiontype"></a>

## ForwardedIPPositionType

```python
from types_aiobotocore_wafv2.literals import ForwardedIPPositionType
```

Values:

- `ANY`
- `FIRST`
- `LAST`

<a id="ipaddressversiontype"></a>

## IPAddressVersionType

```python
from types_aiobotocore_wafv2.literals import IPAddressVersionType
```

Values:

- `IPV4`
- `IPV6`

<a id="jsonmatchscopetype"></a>

## JsonMatchScopeType

```python
from types_aiobotocore_wafv2.literals import JsonMatchScopeType
```

Values:

- `ALL`
- `KEY`
- `VALUE`

<a id="labelmatchscopetype"></a>

## LabelMatchScopeType

```python
from types_aiobotocore_wafv2.literals import LabelMatchScopeType
```

Values:

- `LABEL`
- `NAMESPACE`

<a id="payloadtypetype"></a>

## PayloadTypeType

```python
from types_aiobotocore_wafv2.literals import PayloadTypeType
```

Values:

- `FORM_ENCODED`
- `JSON`

<a id="platformtype"></a>

## PlatformType

```python
from types_aiobotocore_wafv2.literals import PlatformType
```

Values:

- `ANDROID`
- `IOS`

<a id="positionalconstrainttype"></a>

## PositionalConstraintType

```python
from types_aiobotocore_wafv2.literals import PositionalConstraintType
```

Values:

- `CONTAINS`
- `CONTAINS_WORD`
- `ENDS_WITH`
- `EXACTLY`
- `STARTS_WITH`

<a id="ratebasedstatementaggregatekeytypetype"></a>

## RateBasedStatementAggregateKeyTypeType

```python
from types_aiobotocore_wafv2.literals import RateBasedStatementAggregateKeyTypeType
```

Values:

- `FORWARDED_IP`
- `IP`

<a id="resourcetypetype"></a>

## ResourceTypeType

```python
from types_aiobotocore_wafv2.literals import ResourceTypeType
```

Values:

- `API_GATEWAY`
- `APPLICATION_LOAD_BALANCER`
- `APPSYNC`

<a id="responsecontenttypetype"></a>

## ResponseContentTypeType

```python
from types_aiobotocore_wafv2.literals import ResponseContentTypeType
```

Values:

- `APPLICATION_JSON`
- `TEXT_HTML`
- `TEXT_PLAIN`

<a id="scopetype"></a>

## ScopeType

```python
from types_aiobotocore_wafv2.literals import ScopeType
```

Values:

- `CLOUDFRONT`
- `REGIONAL`

<a id="texttransformationtypetype"></a>

## TextTransformationTypeType

```python
from types_aiobotocore_wafv2.literals import TextTransformationTypeType
```

Values:

- `BASE64_DECODE`
- `BASE64_DECODE_EXT`
- `CMD_LINE`
- `COMPRESS_WHITE_SPACE`
- `CSS_DECODE`
- `ESCAPE_SEQ_DECODE`
- `HEX_DECODE`
- `HTML_ENTITY_DECODE`
- `JS_DECODE`
- `LOWERCASE`
- `MD5`
- `NONE`
- `NORMALIZE_PATH`
- `NORMALIZE_PATH_WIN`
- `REMOVE_NULLS`
- `REPLACE_COMMENTS`
- `REPLACE_NULLS`
- `SQL_HEX_DECODE`
- `URL_DECODE`
- `URL_DECODE_UNI`
- `UTF8_TO_UNICODE`

<a id="wafv2servicename"></a>

## WAFV2ServiceName

```python
from types_aiobotocore_wafv2.literals import WAFV2ServiceName
```

Values:

- `wafv2`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_wafv2.literals import ServiceName
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
from types_aiobotocore_wafv2.literals import ResourceServiceName
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
