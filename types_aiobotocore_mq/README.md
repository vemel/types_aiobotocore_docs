<a id="type-annotations-for-aiobotocore-mq-module"></a>

# Type annotations for aiobotocore MQ module

> [Index](..) > MQ

Auto-generated documentation for
[MQ](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mq.html#MQ)
type annotations stubs module
[types-aiobotocore-mq](https://pypi.org/project/types-aiobotocore-mq/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[mq]'

# install as a standalone
pip install types-aiobotocore-mq
```

- [Type annotations for aiobotocore MQ module](#type-annotations-for-aiobotocore-mq-module)
  - [MQClient](#mqclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="mqclient"></a>

## MQClient

Type annotations for `aiobotocore.create_client("mq")` as
[MQClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_mq.client import MQClient
```

<a id="methods"></a>

### Methods

- [can_paginate](./client.md#can_paginate)
- [create_broker](./client.md#create_broker)
- [create_configuration](./client.md#create_configuration)
- [create_tags](./client.md#create_tags)
- [create_user](./client.md#create_user)
- [delete_broker](./client.md#delete_broker)
- [delete_tags](./client.md#delete_tags)
- [delete_user](./client.md#delete_user)
- [describe_broker](./client.md#describe_broker)
- [describe_broker_engine_types](./client.md#describe_broker_engine_types)
- [describe_broker_instance_options](./client.md#describe_broker_instance_options)
- [describe_configuration](./client.md#describe_configuration)
- [describe_configuration_revision](./client.md#describe_configuration_revision)
- [describe_user](./client.md#describe_user)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_paginator](./client.md#get_paginator)
- [list_brokers](./client.md#list_brokers)
- [list_configuration_revisions](./client.md#list_configuration_revisions)
- [list_configurations](./client.md#list_configurations)
- [list_tags](./client.md#list_tags)
- [list_users](./client.md#list_users)
- [reboot_broker](./client.md#reboot_broker)
- [update_broker](./client.md#update_broker)
- [update_configuration](./client.md#update_configuration)
- [update_user](./client.md#update_user)

<a id="exceptions"></a>

### Exceptions

MQClient [exceptions](./client.md#exceptions)

- BadRequestException
- ClientError
- ConflictException
- ForbiddenException
- InternalServerErrorException
- NotFoundException
- UnauthorizedException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("mq").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_mq.paginators import ListBrokersPaginator, ...
```

- [ListBrokersPaginator](./paginators.md#listbrokerspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_mq.literals import AuthenticationStrategyType, ...
```

- [AuthenticationStrategyType](./literals.md#authenticationstrategytype)
- [BrokerStateType](./literals.md#brokerstatetype)
- [BrokerStorageTypeType](./literals.md#brokerstoragetypetype)
- [ChangeTypeType](./literals.md#changetypetype)
- [DayOfWeekType](./literals.md#dayofweektype)
- [DeploymentModeType](./literals.md#deploymentmodetype)
- [EngineTypeType](./literals.md#enginetypetype)
- [ListBrokersPaginatorName](./literals.md#listbrokerspaginatorname)
- [SanitizationWarningReasonType](./literals.md#sanitizationwarningreasontype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_mq.type_defs import AvailabilityZoneTypeDef, ...
```

- [AvailabilityZoneTypeDef](./type_defs.md#availabilityzonetypedef)
- [BrokerEngineTypeTypeDef](./type_defs.md#brokerenginetypetypedef)
- [BrokerInstanceOptionTypeDef](./type_defs.md#brokerinstanceoptiontypedef)
- [BrokerInstanceTypeDef](./type_defs.md#brokerinstancetypedef)
- [BrokerSummaryTypeDef](./type_defs.md#brokersummarytypedef)
- [ConfigurationIdTypeDef](./type_defs.md#configurationidtypedef)
- [ConfigurationRevisionTypeDef](./type_defs.md#configurationrevisiontypedef)
- [ConfigurationTypeDef](./type_defs.md#configurationtypedef)
- [ConfigurationsTypeDef](./type_defs.md#configurationstypedef)
- [CreateBrokerRequestRequestTypeDef](./type_defs.md#createbrokerrequestrequesttypedef)
- [CreateBrokerResponseTypeDef](./type_defs.md#createbrokerresponsetypedef)
- [CreateConfigurationRequestRequestTypeDef](./type_defs.md#createconfigurationrequestrequesttypedef)
- [CreateConfigurationResponseTypeDef](./type_defs.md#createconfigurationresponsetypedef)
- [CreateTagsRequestRequestTypeDef](./type_defs.md#createtagsrequestrequesttypedef)
- [CreateUserRequestRequestTypeDef](./type_defs.md#createuserrequestrequesttypedef)
- [DeleteBrokerRequestRequestTypeDef](./type_defs.md#deletebrokerrequestrequesttypedef)
- [DeleteBrokerResponseTypeDef](./type_defs.md#deletebrokerresponsetypedef)
- [DeleteTagsRequestRequestTypeDef](./type_defs.md#deletetagsrequestrequesttypedef)
- [DeleteUserRequestRequestTypeDef](./type_defs.md#deleteuserrequestrequesttypedef)
- [DescribeBrokerEngineTypesRequestRequestTypeDef](./type_defs.md#describebrokerenginetypesrequestrequesttypedef)
- [DescribeBrokerEngineTypesResponseTypeDef](./type_defs.md#describebrokerenginetypesresponsetypedef)
- [DescribeBrokerInstanceOptionsRequestRequestTypeDef](./type_defs.md#describebrokerinstanceoptionsrequestrequesttypedef)
- [DescribeBrokerInstanceOptionsResponseTypeDef](./type_defs.md#describebrokerinstanceoptionsresponsetypedef)
- [DescribeBrokerRequestRequestTypeDef](./type_defs.md#describebrokerrequestrequesttypedef)
- [DescribeBrokerResponseTypeDef](./type_defs.md#describebrokerresponsetypedef)
- [DescribeConfigurationRequestRequestTypeDef](./type_defs.md#describeconfigurationrequestrequesttypedef)
- [DescribeConfigurationResponseTypeDef](./type_defs.md#describeconfigurationresponsetypedef)
- [DescribeConfigurationRevisionRequestRequestTypeDef](./type_defs.md#describeconfigurationrevisionrequestrequesttypedef)
- [DescribeConfigurationRevisionResponseTypeDef](./type_defs.md#describeconfigurationrevisionresponsetypedef)
- [DescribeUserRequestRequestTypeDef](./type_defs.md#describeuserrequestrequesttypedef)
- [DescribeUserResponseTypeDef](./type_defs.md#describeuserresponsetypedef)
- [EncryptionOptionsTypeDef](./type_defs.md#encryptionoptionstypedef)
- [EngineVersionTypeDef](./type_defs.md#engineversiontypedef)
- [LdapServerMetadataInputTypeDef](./type_defs.md#ldapservermetadatainputtypedef)
- [LdapServerMetadataOutputTypeDef](./type_defs.md#ldapservermetadataoutputtypedef)
- [ListBrokersRequestRequestTypeDef](./type_defs.md#listbrokersrequestrequesttypedef)
- [ListBrokersResponseTypeDef](./type_defs.md#listbrokersresponsetypedef)
- [ListConfigurationRevisionsRequestRequestTypeDef](./type_defs.md#listconfigurationrevisionsrequestrequesttypedef)
- [ListConfigurationRevisionsResponseTypeDef](./type_defs.md#listconfigurationrevisionsresponsetypedef)
- [ListConfigurationsRequestRequestTypeDef](./type_defs.md#listconfigurationsrequestrequesttypedef)
- [ListConfigurationsResponseTypeDef](./type_defs.md#listconfigurationsresponsetypedef)
- [ListTagsRequestRequestTypeDef](./type_defs.md#listtagsrequestrequesttypedef)
- [ListTagsResponseTypeDef](./type_defs.md#listtagsresponsetypedef)
- [ListUsersRequestRequestTypeDef](./type_defs.md#listusersrequestrequesttypedef)
- [ListUsersResponseTypeDef](./type_defs.md#listusersresponsetypedef)
- [LogsSummaryTypeDef](./type_defs.md#logssummarytypedef)
- [LogsTypeDef](./type_defs.md#logstypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PendingLogsTypeDef](./type_defs.md#pendinglogstypedef)
- [RebootBrokerRequestRequestTypeDef](./type_defs.md#rebootbrokerrequestrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [SanitizationWarningTypeDef](./type_defs.md#sanitizationwarningtypedef)
- [UpdateBrokerRequestRequestTypeDef](./type_defs.md#updatebrokerrequestrequesttypedef)
- [UpdateBrokerResponseTypeDef](./type_defs.md#updatebrokerresponsetypedef)
- [UpdateConfigurationRequestRequestTypeDef](./type_defs.md#updateconfigurationrequestrequesttypedef)
- [UpdateConfigurationResponseTypeDef](./type_defs.md#updateconfigurationresponsetypedef)
- [UpdateUserRequestRequestTypeDef](./type_defs.md#updateuserrequestrequesttypedef)
- [UserPendingChangesTypeDef](./type_defs.md#userpendingchangestypedef)
- [UserSummaryTypeDef](./type_defs.md#usersummarytypedef)
- [UserTypeDef](./type_defs.md#usertypedef)
- [WeeklyStartTimeTypeDef](./type_defs.md#weeklystarttimetypedef)
