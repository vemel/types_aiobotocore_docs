<a id="literals-for-aiobotocore-lakeformation-module"></a>

# Literals for aiobotocore LakeFormation module

> [Index](..) > [LakeFormation](.) > Literals

Auto-generated documentation for
[LakeFormation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
type annotations stubs module
[types-aiobotocore-lakeformation](https://pypi.org/project/types-aiobotocore-lakeformation/).

- [Literals for aiobotocore LakeFormation module](#literals-for-aiobotocore-lakeformation-module)
  - [ComparisonOperatorType](#comparisonoperatortype)
  - [DataLakeResourceTypeType](#datalakeresourcetypetype)
  - [FieldNameStringType](#fieldnamestringtype)
  - [GetWorkUnitsPaginatorName](#getworkunitspaginatorname)
  - [ListDataCellsFilterPaginatorName](#listdatacellsfilterpaginatorname)
  - [ListLFTagsPaginatorName](#listlftagspaginatorname)
  - [OptimizerTypeType](#optimizertypetype)
  - [PermissionType](#permissiontype)
  - [QueryStateStringType](#querystatestringtype)
  - [ResourceShareTypeType](#resourcesharetypetype)
  - [ResourceTypeType](#resourcetypetype)
  - [SearchDatabasesByLFTagsPaginatorName](#searchdatabasesbylftagspaginatorname)
  - [SearchTablesByLFTagsPaginatorName](#searchtablesbylftagspaginatorname)
  - [TransactionStatusFilterType](#transactionstatusfiltertype)
  - [TransactionStatusType](#transactionstatustype)
  - [TransactionTypeType](#transactiontypetype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="comparisonoperatortype"></a>

## ComparisonOperatorType

```python
from types_aiobotocore_lakeformation.literals import ComparisonOperatorType
```

Values:

- `BEGINS_WITH`
- `BETWEEN`
- `CONTAINS`
- `EQ`
- `GE`
- `GT`
- `IN`
- `LE`
- `LT`
- `NE`
- `NOT_CONTAINS`

<a id="datalakeresourcetypetype"></a>

## DataLakeResourceTypeType

```python
from types_aiobotocore_lakeformation.literals import DataLakeResourceTypeType
```

Values:

- `CATALOG`
- `DATA_LOCATION`
- `DATABASE`
- `LF_TAG`
- `LF_TAG_POLICY`
- `LF_TAG_POLICY_DATABASE`
- `LF_TAG_POLICY_TABLE`
- `TABLE`

<a id="fieldnamestringtype"></a>

## FieldNameStringType

```python
from types_aiobotocore_lakeformation.literals import FieldNameStringType
```

Values:

- `LAST_MODIFIED`
- `RESOURCE_ARN`
- `ROLE_ARN`

<a id="getworkunitspaginatorname"></a>

## GetWorkUnitsPaginatorName

```python
from types_aiobotocore_lakeformation.literals import GetWorkUnitsPaginatorName
```

Values:

- `get_work_units`

<a id="listdatacellsfilterpaginatorname"></a>

## ListDataCellsFilterPaginatorName

```python
from types_aiobotocore_lakeformation.literals import ListDataCellsFilterPaginatorName
```

Values:

- `list_data_cells_filter`

<a id="listlftagspaginatorname"></a>

## ListLFTagsPaginatorName

```python
from types_aiobotocore_lakeformation.literals import ListLFTagsPaginatorName
```

Values:

- `list_lf_tags`

<a id="optimizertypetype"></a>

## OptimizerTypeType

```python
from types_aiobotocore_lakeformation.literals import OptimizerTypeType
```

Values:

- `ALL`
- `COMPACTION`
- `GARBAGE_COLLECTION`

<a id="permissiontype"></a>

## PermissionType

```python
from types_aiobotocore_lakeformation.literals import PermissionType
```

Values:

- `ALL`
- `ALTER`
- `ALTER_TAG`
- `ASSOCIATE_TAG`
- `CREATE_DATABASE`
- `CREATE_TABLE`
- `CREATE_TAG`
- `DATA_LOCATION_ACCESS`
- `DELETE`
- `DELETE_TAG`
- `DESCRIBE`
- `DESCRIBE_TAG`
- `DROP`
- `INSERT`
- `SELECT`

<a id="querystatestringtype"></a>

## QueryStateStringType

```python
from types_aiobotocore_lakeformation.literals import QueryStateStringType
```

Values:

- `ERROR`
- `EXPIRED`
- `FINISHED`
- `PENDING`
- `WORKUNITS_AVAILABLE`

<a id="resourcesharetypetype"></a>

## ResourceShareTypeType

```python
from types_aiobotocore_lakeformation.literals import ResourceShareTypeType
```

Values:

- `ALL`
- `FOREIGN`

<a id="resourcetypetype"></a>

## ResourceTypeType

```python
from types_aiobotocore_lakeformation.literals import ResourceTypeType
```

Values:

- `DATABASE`
- `TABLE`

<a id="searchdatabasesbylftagspaginatorname"></a>

## SearchDatabasesByLFTagsPaginatorName

```python
from types_aiobotocore_lakeformation.literals import SearchDatabasesByLFTagsPaginatorName
```

Values:

- `search_databases_by_lf_tags`

<a id="searchtablesbylftagspaginatorname"></a>

## SearchTablesByLFTagsPaginatorName

```python
from types_aiobotocore_lakeformation.literals import SearchTablesByLFTagsPaginatorName
```

Values:

- `search_tables_by_lf_tags`

<a id="transactionstatusfiltertype"></a>

## TransactionStatusFilterType

```python
from types_aiobotocore_lakeformation.literals import TransactionStatusFilterType
```

Values:

- `ABORTED`
- `ACTIVE`
- `ALL`
- `COMMITTED`
- `COMPLETED`

<a id="transactionstatustype"></a>

## TransactionStatusType

```python
from types_aiobotocore_lakeformation.literals import TransactionStatusType
```

Values:

- `ABORTED`
- `ACTIVE`
- `COMMIT_IN_PROGRESS`
- `COMMITTED`

<a id="transactiontypetype"></a>

## TransactionTypeType

```python
from types_aiobotocore_lakeformation.literals import TransactionTypeType
```

Values:

- `READ_AND_WRITE`
- `READ_ONLY`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_lakeformation.literals import ServiceName
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
from types_aiobotocore_lakeformation.literals import PaginatorName
```

Values:

- `get_work_units`
- `list_data_cells_filter`
- `list_lf_tags`
- `search_databases_by_lf_tags`
- `search_tables_by_lf_tags`
