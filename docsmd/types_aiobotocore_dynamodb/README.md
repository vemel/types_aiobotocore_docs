# DynamoDB module

> [Index](../README.md) > DynamoDB


!!! note ""

    Auto-generated documentation for [DynamoDB](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
    type annotations stubs module [types-aiobotocore-dynamodb](https://pypi.org/project/types-aiobotocore-dynamodb/).

## How to install

### VSCode extension

Add [AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `DynamoDB`.

### From PyPI with pip

Install `types-aiobotocore` for `DynamoDB` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[dynamodb]'


# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[dynamodb]'


# standalone installation
python -m pip install types-aiobotocore-dynamodb
```


### From conda-forge

Installing `types-aiobotocore-dynamodb` from the `conda-forge` channel
can be achieved by adding `conda-forge` to your channels with:

```bash
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `types-aiobotocore-dynamodb`
can be installed with:

```bash
conda install types-aiobotocore-dynamodb
```

It is possible to list all of the versions of `types-aiobotocore-dynamodb`
available on your platform with:

```bash
conda search types-aiobotocore-dynamodb --channel conda-forge
```


## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-dynamodb
```

## Usage

Code samples can be found in [Examples](./usage.md).

## DynamoDBClient

Type annotations and code completion for  `#!python session.create_client("dynamodb")` as [DynamoDBClient](./client.md)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client)

```python title="Usage example"
from aiobotocore.session import get_session

from types_aiobotocore_dynamodb.client import DynamoDBClient


session = get_session()
async with session.create_client("dynamodb") as client:
    client: DynamoDBClient
```


## Paginators

Type annotations and code completion for
[paginators](./paginators.md)
from `#!python session.create_client("dynamodb").get_paginator("...")`.

```python title="Usage example"
from types_aiobotocore_dynamodb.paginator import ListBackupsPaginator

def get_list_backups_paginator() -> ListBackupsPaginator:
    return client.get_paginator("list_backups"))
```

- [ListBackupsPaginator](./paginators.md#listbackupspaginator)
- [ListTablesPaginator](./paginators.md#listtablespaginator)
- [ListTagsOfResourcePaginator](./paginators.md#listtagsofresourcepaginator)
- [QueryPaginator](./paginators.md#querypaginator)
- [ScanPaginator](./paginators.md#scanpaginator)




## Waiters

Type annotations and code completion for
[waiters](./waiters.md)
from `#!python session.create_client("dynamodb").get_waiter("...")`.

```python title="Usage example"
from types_aiobotocore_dynamodb.waiter import TableExistsWaiter

def get_table_exists_waiter() -> TableExistsWaiter:
    return Session().client("dynamodb").get_waiter("table_exists")
```

- [TableExistsWaiter](./waiters.md#tableexistswaiter)
- [TableNotExistsWaiter](./waiters.md#tablenotexistswaiter)




## DynamoDBServiceResource

Type annotations and code completion for `#!python session.resource("dynamodb")` as
[DynamoDBServiceResource](./service_resource.md#dynamodbserviceresource)
[:material-aws: boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.ServiceResource)

```python title="Usage example"
from types_aiobotocore_dynamodb.service_resource import DynamoDBServiceResource
```


### Collections

Type annotations and code completion for collections
from `#!python session.resource("dynamodb").*`.

```python title="Usage example"
from types_aiobotocore_dynamodb.service_resource import ServiceResourceTablesCollection

def get_collection() -> ServiceResourceTablesCollection:
    return resource.tables
```

- [ServiceResourceTablesCollection](./service_resource.md#dynamodbserviceresourcetables)




### Resources

Type annotations and code completion for additional resources
from `#!python session.resource("dynamodb").*`.

```python title="Usage example"
from types_aiobotocore_dynamodb.service_resource import Table

def get_resource() -> Table:
    return resource.Table(...)
```

- [Table](./service_resource.md#table)





## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_dynamodb.literals import AttributeActionType

def get_value() -> AttributeActionType:
    return "ADD"
```

- [AttributeActionType](./literals.md#attributeactiontype)
- [BackupStatusType](./literals.md#backupstatustype)
- [BackupTypeFilterType](./literals.md#backuptypefiltertype)
- [BackupTypeType](./literals.md#backuptypetype)
- [BatchStatementErrorCodeEnumType](./literals.md#batchstatementerrorcodeenumtype)
- [BillingModeType](./literals.md#billingmodetype)
- [ComparisonOperatorType](./literals.md#comparisonoperatortype)
- [ConditionalOperatorType](./literals.md#conditionaloperatortype)
- [ContinuousBackupsStatusType](./literals.md#continuousbackupsstatustype)
- [ContributorInsightsActionType](./literals.md#contributorinsightsactiontype)
- [ContributorInsightsStatusType](./literals.md#contributorinsightsstatustype)
- [DestinationStatusType](./literals.md#destinationstatustype)
- [ExportFormatType](./literals.md#exportformattype)
- [ExportStatusType](./literals.md#exportstatustype)
- [GlobalTableStatusType](./literals.md#globaltablestatustype)
- [IndexStatusType](./literals.md#indexstatustype)
- [KeyTypeType](./literals.md#keytypetype)
- [ListBackupsPaginatorName](./literals.md#listbackupspaginatorname)
- [ListTablesPaginatorName](./literals.md#listtablespaginatorname)
- [ListTagsOfResourcePaginatorName](./literals.md#listtagsofresourcepaginatorname)
- [PointInTimeRecoveryStatusType](./literals.md#pointintimerecoverystatustype)
- [ProjectionTypeType](./literals.md#projectiontypetype)
- [QueryPaginatorName](./literals.md#querypaginatorname)
- [ReplicaStatusType](./literals.md#replicastatustype)
- [ReturnConsumedCapacityType](./literals.md#returnconsumedcapacitytype)
- [ReturnItemCollectionMetricsType](./literals.md#returnitemcollectionmetricstype)
- [ReturnValueType](./literals.md#returnvaluetype)
- [ReturnValuesOnConditionCheckFailureType](./literals.md#returnvaluesonconditioncheckfailuretype)
- [S3SseAlgorithmType](./literals.md#s3ssealgorithmtype)
- [SSEStatusType](./literals.md#ssestatustype)
- [SSETypeType](./literals.md#ssetypetype)
- [ScalarAttributeTypeType](./literals.md#scalarattributetypetype)
- [ScanPaginatorName](./literals.md#scanpaginatorname)
- [SelectType](./literals.md#selecttype)
- [StreamViewTypeType](./literals.md#streamviewtypetype)
- [TableClassType](./literals.md#tableclasstype)
- [TableExistsWaiterName](./literals.md#tableexistswaitername)
- [TableNotExistsWaiterName](./literals.md#tablenotexistswaitername)
- [TableStatusType](./literals.md#tablestatustype)
- [TimeToLiveStatusType](./literals.md#timetolivestatustype)
- [DynamoDBServiceName](./literals.md#dynamodbservicename)
- [ServiceName](./literals.md#servicename)
- [ResourceServiceName](./literals.md#resourceservicename)
- [PaginatorName](./literals.md#paginatorname)
- [WaiterName](./literals.md#waitername)
- [RegionName](./literals.md#regionname)




## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and schema.

```python title="Usage example"
from types_aiobotocore_dynamodb.type_defs import ArchivalSummaryResponseMetadataTypeDef

def get_value() -> ArchivalSummaryResponseMetadataTypeDef:
    return {
        "ArchivalDateTime": ...,
        "ArchivalReason": ...,
        "ArchivalBackupArn": ...,
        "ResponseMetadata": ...,
    }
```

- [ArchivalSummaryResponseMetadataTypeDef](./type_defs.md#archivalsummaryresponsemetadatatypedef)
- [ArchivalSummaryTypeDef](./type_defs.md#archivalsummarytypedef)
- [AttributeDefinitionTypeDef](./type_defs.md#attributedefinitiontypedef)
- [AttributeValueUpdateTypeDef](./type_defs.md#attributevalueupdatetypedef)
- [AutoScalingPolicyDescriptionTypeDef](./type_defs.md#autoscalingpolicydescriptiontypedef)
- [AutoScalingPolicyUpdateTypeDef](./type_defs.md#autoscalingpolicyupdatetypedef)
- [AutoScalingSettingsDescriptionTypeDef](./type_defs.md#autoscalingsettingsdescriptiontypedef)
- [AutoScalingSettingsUpdateTypeDef](./type_defs.md#autoscalingsettingsupdatetypedef)
- [AutoScalingTargetTrackingScalingPolicyConfigurationDescriptionTypeDef](./type_defs.md#autoscalingtargettrackingscalingpolicyconfigurationdescriptiontypedef)
- [AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef](./type_defs.md#autoscalingtargettrackingscalingpolicyconfigurationupdatetypedef)
- [BackupDescriptionTypeDef](./type_defs.md#backupdescriptiontypedef)
- [BackupDetailsTypeDef](./type_defs.md#backupdetailstypedef)
- [BackupSummaryTypeDef](./type_defs.md#backupsummarytypedef)
- [BatchExecuteStatementInputRequestTypeDef](./type_defs.md#batchexecutestatementinputrequesttypedef)
- [BatchExecuteStatementOutputTypeDef](./type_defs.md#batchexecutestatementoutputtypedef)
- [BatchGetItemInputRequestTypeDef](./type_defs.md#batchgetiteminputrequesttypedef)
- [BatchGetItemInputServiceResourceBatchGetItemTypeDef](./type_defs.md#batchgetiteminputserviceresourcebatchgetitemtypedef)
- [BatchGetItemOutputTypeDef](./type_defs.md#batchgetitemoutputtypedef)
- [BatchStatementErrorTypeDef](./type_defs.md#batchstatementerrortypedef)
- [BatchStatementRequestTypeDef](./type_defs.md#batchstatementrequesttypedef)
- [BatchStatementResponseTypeDef](./type_defs.md#batchstatementresponsetypedef)
- [BatchWriteItemInputRequestTypeDef](./type_defs.md#batchwriteiteminputrequesttypedef)
- [BatchWriteItemInputServiceResourceBatchWriteItemTypeDef](./type_defs.md#batchwriteiteminputserviceresourcebatchwriteitemtypedef)
- [BatchWriteItemOutputTypeDef](./type_defs.md#batchwriteitemoutputtypedef)
- [BillingModeSummaryResponseMetadataTypeDef](./type_defs.md#billingmodesummaryresponsemetadatatypedef)
- [BillingModeSummaryTypeDef](./type_defs.md#billingmodesummarytypedef)
- [CapacityTypeDef](./type_defs.md#capacitytypedef)
- [ConditionCheckTypeDef](./type_defs.md#conditionchecktypedef)
- [ConditionTypeDef](./type_defs.md#conditiontypedef)
- [ConsumedCapacityTypeDef](./type_defs.md#consumedcapacitytypedef)
- [ContinuousBackupsDescriptionTypeDef](./type_defs.md#continuousbackupsdescriptiontypedef)
- [ContributorInsightsSummaryTypeDef](./type_defs.md#contributorinsightssummarytypedef)
- [CreateBackupInputRequestTypeDef](./type_defs.md#createbackupinputrequesttypedef)
- [CreateBackupOutputTypeDef](./type_defs.md#createbackupoutputtypedef)
- [CreateGlobalSecondaryIndexActionTypeDef](./type_defs.md#createglobalsecondaryindexactiontypedef)
- [CreateGlobalTableInputRequestTypeDef](./type_defs.md#createglobaltableinputrequesttypedef)
- [CreateGlobalTableOutputTypeDef](./type_defs.md#createglobaltableoutputtypedef)
- [CreateReplicaActionTypeDef](./type_defs.md#createreplicaactiontypedef)
- [CreateReplicationGroupMemberActionTypeDef](./type_defs.md#createreplicationgroupmemberactiontypedef)
- [CreateTableInputRequestTypeDef](./type_defs.md#createtableinputrequesttypedef)
- [CreateTableInputServiceResourceCreateTableTypeDef](./type_defs.md#createtableinputserviceresourcecreatetabletypedef)
- [CreateTableOutputTypeDef](./type_defs.md#createtableoutputtypedef)
- [DeleteBackupInputRequestTypeDef](./type_defs.md#deletebackupinputrequesttypedef)
- [DeleteBackupOutputTypeDef](./type_defs.md#deletebackupoutputtypedef)
- [DeleteGlobalSecondaryIndexActionTypeDef](./type_defs.md#deleteglobalsecondaryindexactiontypedef)
- [DeleteItemInputRequestTypeDef](./type_defs.md#deleteiteminputrequesttypedef)
- [DeleteItemInputTableDeleteItemTypeDef](./type_defs.md#deleteiteminputtabledeleteitemtypedef)
- [DeleteItemOutputTypeDef](./type_defs.md#deleteitemoutputtypedef)
- [DeleteReplicaActionTypeDef](./type_defs.md#deletereplicaactiontypedef)
- [DeleteReplicationGroupMemberActionTypeDef](./type_defs.md#deletereplicationgroupmemberactiontypedef)
- [DeleteRequestTypeDef](./type_defs.md#deleterequesttypedef)
- [DeleteTableInputRequestTypeDef](./type_defs.md#deletetableinputrequesttypedef)
- [DeleteTableOutputTypeDef](./type_defs.md#deletetableoutputtypedef)
- [DeleteTypeDef](./type_defs.md#deletetypedef)
- [DescribeBackupInputRequestTypeDef](./type_defs.md#describebackupinputrequesttypedef)
- [DescribeBackupOutputTypeDef](./type_defs.md#describebackupoutputtypedef)
- [DescribeContinuousBackupsInputRequestTypeDef](./type_defs.md#describecontinuousbackupsinputrequesttypedef)
- [DescribeContinuousBackupsOutputTypeDef](./type_defs.md#describecontinuousbackupsoutputtypedef)
- [DescribeContributorInsightsInputRequestTypeDef](./type_defs.md#describecontributorinsightsinputrequesttypedef)
- [DescribeContributorInsightsOutputTypeDef](./type_defs.md#describecontributorinsightsoutputtypedef)
- [DescribeEndpointsResponseTypeDef](./type_defs.md#describeendpointsresponsetypedef)
- [DescribeExportInputRequestTypeDef](./type_defs.md#describeexportinputrequesttypedef)
- [DescribeExportOutputTypeDef](./type_defs.md#describeexportoutputtypedef)
- [DescribeGlobalTableInputRequestTypeDef](./type_defs.md#describeglobaltableinputrequesttypedef)
- [DescribeGlobalTableOutputTypeDef](./type_defs.md#describeglobaltableoutputtypedef)
- [DescribeGlobalTableSettingsInputRequestTypeDef](./type_defs.md#describeglobaltablesettingsinputrequesttypedef)
- [DescribeGlobalTableSettingsOutputTypeDef](./type_defs.md#describeglobaltablesettingsoutputtypedef)
- [DescribeKinesisStreamingDestinationInputRequestTypeDef](./type_defs.md#describekinesisstreamingdestinationinputrequesttypedef)
- [DescribeKinesisStreamingDestinationOutputTypeDef](./type_defs.md#describekinesisstreamingdestinationoutputtypedef)
- [DescribeLimitsOutputTypeDef](./type_defs.md#describelimitsoutputtypedef)
- [DescribeTableInputRequestTypeDef](./type_defs.md#describetableinputrequesttypedef)
- [DescribeTableInputTableExistsWaitTypeDef](./type_defs.md#describetableinputtableexistswaittypedef)
- [DescribeTableInputTableNotExistsWaitTypeDef](./type_defs.md#describetableinputtablenotexistswaittypedef)
- [DescribeTableOutputTypeDef](./type_defs.md#describetableoutputtypedef)
- [DescribeTableReplicaAutoScalingInputRequestTypeDef](./type_defs.md#describetablereplicaautoscalinginputrequesttypedef)
- [DescribeTableReplicaAutoScalingOutputTypeDef](./type_defs.md#describetablereplicaautoscalingoutputtypedef)
- [DescribeTimeToLiveInputRequestTypeDef](./type_defs.md#describetimetoliveinputrequesttypedef)
- [DescribeTimeToLiveOutputTypeDef](./type_defs.md#describetimetoliveoutputtypedef)
- [EndpointTypeDef](./type_defs.md#endpointtypedef)
- [ExecuteStatementInputRequestTypeDef](./type_defs.md#executestatementinputrequesttypedef)
- [ExecuteStatementOutputTypeDef](./type_defs.md#executestatementoutputtypedef)
- [ExecuteTransactionInputRequestTypeDef](./type_defs.md#executetransactioninputrequesttypedef)
- [ExecuteTransactionOutputTypeDef](./type_defs.md#executetransactionoutputtypedef)
- [ExpectedAttributeValueTypeDef](./type_defs.md#expectedattributevaluetypedef)
- [ExportDescriptionTypeDef](./type_defs.md#exportdescriptiontypedef)
- [ExportSummaryTypeDef](./type_defs.md#exportsummarytypedef)
- [ExportTableToPointInTimeInputRequestTypeDef](./type_defs.md#exporttabletopointintimeinputrequesttypedef)
- [ExportTableToPointInTimeOutputTypeDef](./type_defs.md#exporttabletopointintimeoutputtypedef)
- [FailureExceptionTypeDef](./type_defs.md#failureexceptiontypedef)
- [GetItemInputRequestTypeDef](./type_defs.md#getiteminputrequesttypedef)
- [GetItemInputTableGetItemTypeDef](./type_defs.md#getiteminputtablegetitemtypedef)
- [GetItemOutputTypeDef](./type_defs.md#getitemoutputtypedef)
- [GetTypeDef](./type_defs.md#gettypedef)
- [GlobalSecondaryIndexAutoScalingUpdateTypeDef](./type_defs.md#globalsecondaryindexautoscalingupdatetypedef)
- [GlobalSecondaryIndexDescriptionTypeDef](./type_defs.md#globalsecondaryindexdescriptiontypedef)
- [GlobalSecondaryIndexInfoTypeDef](./type_defs.md#globalsecondaryindexinfotypedef)
- [GlobalSecondaryIndexTypeDef](./type_defs.md#globalsecondaryindextypedef)
- [GlobalSecondaryIndexUpdateTypeDef](./type_defs.md#globalsecondaryindexupdatetypedef)
- [GlobalTableDescriptionTypeDef](./type_defs.md#globaltabledescriptiontypedef)
- [GlobalTableGlobalSecondaryIndexSettingsUpdateTypeDef](./type_defs.md#globaltableglobalsecondaryindexsettingsupdatetypedef)
- [GlobalTableTypeDef](./type_defs.md#globaltabletypedef)
- [ItemCollectionMetricsTypeDef](./type_defs.md#itemcollectionmetricstypedef)
- [ItemResponseTypeDef](./type_defs.md#itemresponsetypedef)
- [KeySchemaElementTypeDef](./type_defs.md#keyschemaelementtypedef)
- [KeysAndAttributesTypeDef](./type_defs.md#keysandattributestypedef)
- [KinesisDataStreamDestinationTypeDef](./type_defs.md#kinesisdatastreamdestinationtypedef)
- [KinesisStreamingDestinationInputRequestTypeDef](./type_defs.md#kinesisstreamingdestinationinputrequesttypedef)
- [KinesisStreamingDestinationOutputTypeDef](./type_defs.md#kinesisstreamingdestinationoutputtypedef)
- [ListBackupsInputListBackupsPaginateTypeDef](./type_defs.md#listbackupsinputlistbackupspaginatetypedef)
- [ListBackupsInputRequestTypeDef](./type_defs.md#listbackupsinputrequesttypedef)
- [ListBackupsOutputTypeDef](./type_defs.md#listbackupsoutputtypedef)
- [ListContributorInsightsInputRequestTypeDef](./type_defs.md#listcontributorinsightsinputrequesttypedef)
- [ListContributorInsightsOutputTypeDef](./type_defs.md#listcontributorinsightsoutputtypedef)
- [ListExportsInputRequestTypeDef](./type_defs.md#listexportsinputrequesttypedef)
- [ListExportsOutputTypeDef](./type_defs.md#listexportsoutputtypedef)
- [ListGlobalTablesInputRequestTypeDef](./type_defs.md#listglobaltablesinputrequesttypedef)
- [ListGlobalTablesOutputTypeDef](./type_defs.md#listglobaltablesoutputtypedef)
- [ListTablesInputListTablesPaginateTypeDef](./type_defs.md#listtablesinputlisttablespaginatetypedef)
- [ListTablesInputRequestTypeDef](./type_defs.md#listtablesinputrequesttypedef)
- [ListTablesOutputTypeDef](./type_defs.md#listtablesoutputtypedef)
- [ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef](./type_defs.md#listtagsofresourceinputlisttagsofresourcepaginatetypedef)
- [ListTagsOfResourceInputRequestTypeDef](./type_defs.md#listtagsofresourceinputrequesttypedef)
- [ListTagsOfResourceOutputTypeDef](./type_defs.md#listtagsofresourceoutputtypedef)
- [LocalSecondaryIndexDescriptionTypeDef](./type_defs.md#localsecondaryindexdescriptiontypedef)
- [LocalSecondaryIndexInfoTypeDef](./type_defs.md#localsecondaryindexinfotypedef)
- [LocalSecondaryIndexTypeDef](./type_defs.md#localsecondaryindextypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [ParameterizedStatementTypeDef](./type_defs.md#parameterizedstatementtypedef)
- [PointInTimeRecoveryDescriptionTypeDef](./type_defs.md#pointintimerecoverydescriptiontypedef)
- [PointInTimeRecoverySpecificationTypeDef](./type_defs.md#pointintimerecoveryspecificationtypedef)
- [ProjectionTypeDef](./type_defs.md#projectiontypedef)
- [ProvisionedThroughputDescriptionResponseMetadataTypeDef](./type_defs.md#provisionedthroughputdescriptionresponsemetadatatypedef)
- [ProvisionedThroughputDescriptionTypeDef](./type_defs.md#provisionedthroughputdescriptiontypedef)
- [ProvisionedThroughputOverrideTypeDef](./type_defs.md#provisionedthroughputoverridetypedef)
- [ProvisionedThroughputTypeDef](./type_defs.md#provisionedthroughputtypedef)
- [PutItemInputRequestTypeDef](./type_defs.md#putiteminputrequesttypedef)
- [PutItemInputTablePutItemTypeDef](./type_defs.md#putiteminputtableputitemtypedef)
- [PutItemOutputTypeDef](./type_defs.md#putitemoutputtypedef)
- [PutRequestTypeDef](./type_defs.md#putrequesttypedef)
- [PutTypeDef](./type_defs.md#puttypedef)
- [QueryInputQueryPaginateTypeDef](./type_defs.md#queryinputquerypaginatetypedef)
- [QueryInputRequestTypeDef](./type_defs.md#queryinputrequesttypedef)
- [QueryInputTableQueryTypeDef](./type_defs.md#queryinputtablequerytypedef)
- [QueryOutputTypeDef](./type_defs.md#queryoutputtypedef)
- [ReplicaAutoScalingDescriptionTypeDef](./type_defs.md#replicaautoscalingdescriptiontypedef)
- [ReplicaAutoScalingUpdateTypeDef](./type_defs.md#replicaautoscalingupdatetypedef)
- [ReplicaDescriptionTypeDef](./type_defs.md#replicadescriptiontypedef)
- [ReplicaGlobalSecondaryIndexAutoScalingDescriptionTypeDef](./type_defs.md#replicaglobalsecondaryindexautoscalingdescriptiontypedef)
- [ReplicaGlobalSecondaryIndexAutoScalingUpdateTypeDef](./type_defs.md#replicaglobalsecondaryindexautoscalingupdatetypedef)
- [ReplicaGlobalSecondaryIndexDescriptionTypeDef](./type_defs.md#replicaglobalsecondaryindexdescriptiontypedef)
- [ReplicaGlobalSecondaryIndexSettingsDescriptionTypeDef](./type_defs.md#replicaglobalsecondaryindexsettingsdescriptiontypedef)
- [ReplicaGlobalSecondaryIndexSettingsUpdateTypeDef](./type_defs.md#replicaglobalsecondaryindexsettingsupdatetypedef)
- [ReplicaGlobalSecondaryIndexTypeDef](./type_defs.md#replicaglobalsecondaryindextypedef)
- [ReplicaSettingsDescriptionTypeDef](./type_defs.md#replicasettingsdescriptiontypedef)
- [ReplicaSettingsUpdateTypeDef](./type_defs.md#replicasettingsupdatetypedef)
- [ReplicaTypeDef](./type_defs.md#replicatypedef)
- [ReplicaUpdateTypeDef](./type_defs.md#replicaupdatetypedef)
- [ReplicationGroupUpdateTypeDef](./type_defs.md#replicationgroupupdatetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RestoreSummaryResponseMetadataTypeDef](./type_defs.md#restoresummaryresponsemetadatatypedef)
- [RestoreSummaryTypeDef](./type_defs.md#restoresummarytypedef)
- [RestoreTableFromBackupInputRequestTypeDef](./type_defs.md#restoretablefrombackupinputrequesttypedef)
- [RestoreTableFromBackupOutputTypeDef](./type_defs.md#restoretablefrombackupoutputtypedef)
- [RestoreTableToPointInTimeInputRequestTypeDef](./type_defs.md#restoretabletopointintimeinputrequesttypedef)
- [RestoreTableToPointInTimeOutputTypeDef](./type_defs.md#restoretabletopointintimeoutputtypedef)
- [SSEDescriptionResponseMetadataTypeDef](./type_defs.md#ssedescriptionresponsemetadatatypedef)
- [SSEDescriptionTypeDef](./type_defs.md#ssedescriptiontypedef)
- [SSESpecificationTypeDef](./type_defs.md#ssespecificationtypedef)
- [ScanInputRequestTypeDef](./type_defs.md#scaninputrequesttypedef)
- [ScanInputScanPaginateTypeDef](./type_defs.md#scaninputscanpaginatetypedef)
- [ScanInputTableScanTypeDef](./type_defs.md#scaninputtablescantypedef)
- [ScanOutputTypeDef](./type_defs.md#scanoutputtypedef)
- [ServiceResourceTableRequestTypeDef](./type_defs.md#serviceresourcetablerequesttypedef)
- [SourceTableDetailsTypeDef](./type_defs.md#sourcetabledetailstypedef)
- [SourceTableFeatureDetailsTypeDef](./type_defs.md#sourcetablefeaturedetailstypedef)
- [StreamSpecificationResponseMetadataTypeDef](./type_defs.md#streamspecificationresponsemetadatatypedef)
- [StreamSpecificationTypeDef](./type_defs.md#streamspecificationtypedef)
- [TableAutoScalingDescriptionTypeDef](./type_defs.md#tableautoscalingdescriptiontypedef)
- [TableBatchWriterRequestTypeDef](./type_defs.md#tablebatchwriterrequesttypedef)
- [TableClassSummaryResponseMetadataTypeDef](./type_defs.md#tableclasssummaryresponsemetadatatypedef)
- [TableClassSummaryTypeDef](./type_defs.md#tableclasssummarytypedef)
- [TableDescriptionTypeDef](./type_defs.md#tabledescriptiontypedef)
- [TagResourceInputRequestTypeDef](./type_defs.md#tagresourceinputrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TimeToLiveDescriptionTypeDef](./type_defs.md#timetolivedescriptiontypedef)
- [TimeToLiveSpecificationTypeDef](./type_defs.md#timetolivespecificationtypedef)
- [TransactGetItemTypeDef](./type_defs.md#transactgetitemtypedef)
- [TransactGetItemsInputRequestTypeDef](./type_defs.md#transactgetitemsinputrequesttypedef)
- [TransactGetItemsOutputTypeDef](./type_defs.md#transactgetitemsoutputtypedef)
- [TransactWriteItemTypeDef](./type_defs.md#transactwriteitemtypedef)
- [TransactWriteItemsInputRequestTypeDef](./type_defs.md#transactwriteitemsinputrequesttypedef)
- [TransactWriteItemsOutputTypeDef](./type_defs.md#transactwriteitemsoutputtypedef)
- [UntagResourceInputRequestTypeDef](./type_defs.md#untagresourceinputrequesttypedef)
- [UpdateContinuousBackupsInputRequestTypeDef](./type_defs.md#updatecontinuousbackupsinputrequesttypedef)
- [UpdateContinuousBackupsOutputTypeDef](./type_defs.md#updatecontinuousbackupsoutputtypedef)
- [UpdateContributorInsightsInputRequestTypeDef](./type_defs.md#updatecontributorinsightsinputrequesttypedef)
- [UpdateContributorInsightsOutputTypeDef](./type_defs.md#updatecontributorinsightsoutputtypedef)
- [UpdateGlobalSecondaryIndexActionTypeDef](./type_defs.md#updateglobalsecondaryindexactiontypedef)
- [UpdateGlobalTableInputRequestTypeDef](./type_defs.md#updateglobaltableinputrequesttypedef)
- [UpdateGlobalTableOutputTypeDef](./type_defs.md#updateglobaltableoutputtypedef)
- [UpdateGlobalTableSettingsInputRequestTypeDef](./type_defs.md#updateglobaltablesettingsinputrequesttypedef)
- [UpdateGlobalTableSettingsOutputTypeDef](./type_defs.md#updateglobaltablesettingsoutputtypedef)
- [UpdateItemInputRequestTypeDef](./type_defs.md#updateiteminputrequesttypedef)
- [UpdateItemInputTableUpdateItemTypeDef](./type_defs.md#updateiteminputtableupdateitemtypedef)
- [UpdateItemOutputTypeDef](./type_defs.md#updateitemoutputtypedef)
- [UpdateReplicationGroupMemberActionTypeDef](./type_defs.md#updatereplicationgroupmemberactiontypedef)
- [UpdateTableInputRequestTypeDef](./type_defs.md#updatetableinputrequesttypedef)
- [UpdateTableInputTableUpdateTypeDef](./type_defs.md#updatetableinputtableupdatetypedef)
- [UpdateTableOutputTypeDef](./type_defs.md#updatetableoutputtypedef)
- [UpdateTableReplicaAutoScalingInputRequestTypeDef](./type_defs.md#updatetablereplicaautoscalinginputrequesttypedef)
- [UpdateTableReplicaAutoScalingOutputTypeDef](./type_defs.md#updatetablereplicaautoscalingoutputtypedef)
- [UpdateTimeToLiveInputRequestTypeDef](./type_defs.md#updatetimetoliveinputrequesttypedef)
- [UpdateTimeToLiveOutputTypeDef](./type_defs.md#updatetimetoliveoutputtypedef)
- [UpdateTypeDef](./type_defs.md#updatetypedef)
- [WaiterConfigTypeDef](./type_defs.md#waiterconfigtypedef)
- [WriteRequestTypeDef](./type_defs.md#writerequesttypedef)

