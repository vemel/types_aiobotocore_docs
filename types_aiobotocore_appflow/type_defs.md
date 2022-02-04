<a id="typed-dictionaries-for-aiobotocore-appflow-module"></a>

# Typed dictionaries for aiobotocore Appflow module

> [Index](..) > [Appflow](.) > Typed dictionaries

Auto-generated documentation for
[Appflow](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
type annotations stubs module
[types-aiobotocore-appflow](https://pypi.org/project/types-aiobotocore-appflow/).

- [Typed dictionaries for aiobotocore Appflow module](#typed-dictionaries-for-aiobotocore-appflow-module)
  - [AggregationConfigTypeDef](#aggregationconfigtypedef)
  - [AmplitudeConnectorProfileCredentialsTypeDef](#amplitudeconnectorprofilecredentialstypedef)
  - [AmplitudeSourcePropertiesTypeDef](#amplitudesourcepropertiestypedef)
  - [BasicAuthCredentialsTypeDef](#basicauthcredentialstypedef)
  - [ConnectorConfigurationTypeDef](#connectorconfigurationtypedef)
  - [ConnectorEntityFieldTypeDef](#connectorentityfieldtypedef)
  - [ConnectorEntityTypeDef](#connectorentitytypedef)
  - [ConnectorMetadataTypeDef](#connectormetadatatypedef)
  - [ConnectorOAuthRequestTypeDef](#connectoroauthrequesttypedef)
  - [ConnectorOperatorTypeDef](#connectoroperatortypedef)
  - [ConnectorProfileConfigTypeDef](#connectorprofileconfigtypedef)
  - [ConnectorProfileCredentialsTypeDef](#connectorprofilecredentialstypedef)
  - [ConnectorProfilePropertiesTypeDef](#connectorprofilepropertiestypedef)
  - [ConnectorProfileTypeDef](#connectorprofiletypedef)
  - [CreateConnectorProfileRequestRequestTypeDef](#createconnectorprofilerequestrequesttypedef)
  - [CreateConnectorProfileResponseTypeDef](#createconnectorprofileresponsetypedef)
  - [CreateFlowRequestRequestTypeDef](#createflowrequestrequesttypedef)
  - [CreateFlowResponseTypeDef](#createflowresponsetypedef)
  - [CustomerProfilesDestinationPropertiesTypeDef](#customerprofilesdestinationpropertiestypedef)
  - [DatadogConnectorProfileCredentialsTypeDef](#datadogconnectorprofilecredentialstypedef)
  - [DatadogConnectorProfilePropertiesTypeDef](#datadogconnectorprofilepropertiestypedef)
  - [DatadogSourcePropertiesTypeDef](#datadogsourcepropertiestypedef)
  - [DeleteConnectorProfileRequestRequestTypeDef](#deleteconnectorprofilerequestrequesttypedef)
  - [DeleteFlowRequestRequestTypeDef](#deleteflowrequestrequesttypedef)
  - [DescribeConnectorEntityRequestRequestTypeDef](#describeconnectorentityrequestrequesttypedef)
  - [DescribeConnectorEntityResponseTypeDef](#describeconnectorentityresponsetypedef)
  - [DescribeConnectorProfilesRequestRequestTypeDef](#describeconnectorprofilesrequestrequesttypedef)
  - [DescribeConnectorProfilesResponseTypeDef](#describeconnectorprofilesresponsetypedef)
  - [DescribeConnectorsRequestRequestTypeDef](#describeconnectorsrequestrequesttypedef)
  - [DescribeConnectorsResponseTypeDef](#describeconnectorsresponsetypedef)
  - [DescribeFlowExecutionRecordsRequestRequestTypeDef](#describeflowexecutionrecordsrequestrequesttypedef)
  - [DescribeFlowExecutionRecordsResponseTypeDef](#describeflowexecutionrecordsresponsetypedef)
  - [DescribeFlowRequestRequestTypeDef](#describeflowrequestrequesttypedef)
  - [DescribeFlowResponseTypeDef](#describeflowresponsetypedef)
  - [DestinationConnectorPropertiesTypeDef](#destinationconnectorpropertiestypedef)
  - [DestinationFieldPropertiesTypeDef](#destinationfieldpropertiestypedef)
  - [DestinationFlowConfigTypeDef](#destinationflowconfigtypedef)
  - [DynatraceConnectorProfileCredentialsTypeDef](#dynatraceconnectorprofilecredentialstypedef)
  - [DynatraceConnectorProfilePropertiesTypeDef](#dynatraceconnectorprofilepropertiestypedef)
  - [DynatraceSourcePropertiesTypeDef](#dynatracesourcepropertiestypedef)
  - [ErrorHandlingConfigTypeDef](#errorhandlingconfigtypedef)
  - [ErrorInfoTypeDef](#errorinfotypedef)
  - [EventBridgeDestinationPropertiesTypeDef](#eventbridgedestinationpropertiestypedef)
  - [ExecutionDetailsTypeDef](#executiondetailstypedef)
  - [ExecutionRecordTypeDef](#executionrecordtypedef)
  - [ExecutionResultTypeDef](#executionresulttypedef)
  - [FieldTypeDetailsTypeDef](#fieldtypedetailstypedef)
  - [FlowDefinitionTypeDef](#flowdefinitiontypedef)
  - [GoogleAnalyticsConnectorProfileCredentialsTypeDef](#googleanalyticsconnectorprofilecredentialstypedef)
  - [GoogleAnalyticsMetadataTypeDef](#googleanalyticsmetadatatypedef)
  - [GoogleAnalyticsSourcePropertiesTypeDef](#googleanalyticssourcepropertiestypedef)
  - [HoneycodeConnectorProfileCredentialsTypeDef](#honeycodeconnectorprofilecredentialstypedef)
  - [HoneycodeDestinationPropertiesTypeDef](#honeycodedestinationpropertiestypedef)
  - [HoneycodeMetadataTypeDef](#honeycodemetadatatypedef)
  - [IncrementalPullConfigTypeDef](#incrementalpullconfigtypedef)
  - [InforNexusConnectorProfileCredentialsTypeDef](#infornexusconnectorprofilecredentialstypedef)
  - [InforNexusConnectorProfilePropertiesTypeDef](#infornexusconnectorprofilepropertiestypedef)
  - [InforNexusSourcePropertiesTypeDef](#infornexussourcepropertiestypedef)
  - [ListConnectorEntitiesRequestRequestTypeDef](#listconnectorentitiesrequestrequesttypedef)
  - [ListConnectorEntitiesResponseTypeDef](#listconnectorentitiesresponsetypedef)
  - [ListFlowsRequestRequestTypeDef](#listflowsrequestrequesttypedef)
  - [ListFlowsResponseTypeDef](#listflowsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MarketoConnectorProfileCredentialsTypeDef](#marketoconnectorprofilecredentialstypedef)
  - [MarketoConnectorProfilePropertiesTypeDef](#marketoconnectorprofilepropertiestypedef)
  - [MarketoSourcePropertiesTypeDef](#marketosourcepropertiestypedef)
  - [OAuthCredentialsTypeDef](#oauthcredentialstypedef)
  - [OAuthPropertiesTypeDef](#oauthpropertiestypedef)
  - [PrefixConfigTypeDef](#prefixconfigtypedef)
  - [PrivateConnectionProvisioningStateTypeDef](#privateconnectionprovisioningstatetypedef)
  - [RedshiftConnectorProfileCredentialsTypeDef](#redshiftconnectorprofilecredentialstypedef)
  - [RedshiftConnectorProfilePropertiesTypeDef](#redshiftconnectorprofilepropertiestypedef)
  - [RedshiftDestinationPropertiesTypeDef](#redshiftdestinationpropertiestypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3DestinationPropertiesTypeDef](#s3destinationpropertiestypedef)
  - [S3InputFormatConfigTypeDef](#s3inputformatconfigtypedef)
  - [S3OutputFormatConfigTypeDef](#s3outputformatconfigtypedef)
  - [S3SourcePropertiesTypeDef](#s3sourcepropertiestypedef)
  - [SAPODataConnectorProfileCredentialsTypeDef](#sapodataconnectorprofilecredentialstypedef)
  - [SAPODataConnectorProfilePropertiesTypeDef](#sapodataconnectorprofilepropertiestypedef)
  - [SAPODataSourcePropertiesTypeDef](#sapodatasourcepropertiestypedef)
  - [SalesforceConnectorProfileCredentialsTypeDef](#salesforceconnectorprofilecredentialstypedef)
  - [SalesforceConnectorProfilePropertiesTypeDef](#salesforceconnectorprofilepropertiestypedef)
  - [SalesforceDestinationPropertiesTypeDef](#salesforcedestinationpropertiestypedef)
  - [SalesforceMetadataTypeDef](#salesforcemetadatatypedef)
  - [SalesforceSourcePropertiesTypeDef](#salesforcesourcepropertiestypedef)
  - [ScheduledTriggerPropertiesTypeDef](#scheduledtriggerpropertiestypedef)
  - [ServiceNowConnectorProfileCredentialsTypeDef](#servicenowconnectorprofilecredentialstypedef)
  - [ServiceNowConnectorProfilePropertiesTypeDef](#servicenowconnectorprofilepropertiestypedef)
  - [ServiceNowSourcePropertiesTypeDef](#servicenowsourcepropertiestypedef)
  - [SingularConnectorProfileCredentialsTypeDef](#singularconnectorprofilecredentialstypedef)
  - [SingularSourcePropertiesTypeDef](#singularsourcepropertiestypedef)
  - [SlackConnectorProfileCredentialsTypeDef](#slackconnectorprofilecredentialstypedef)
  - [SlackConnectorProfilePropertiesTypeDef](#slackconnectorprofilepropertiestypedef)
  - [SlackMetadataTypeDef](#slackmetadatatypedef)
  - [SlackSourcePropertiesTypeDef](#slacksourcepropertiestypedef)
  - [SnowflakeConnectorProfileCredentialsTypeDef](#snowflakeconnectorprofilecredentialstypedef)
  - [SnowflakeConnectorProfilePropertiesTypeDef](#snowflakeconnectorprofilepropertiestypedef)
  - [SnowflakeDestinationPropertiesTypeDef](#snowflakedestinationpropertiestypedef)
  - [SnowflakeMetadataTypeDef](#snowflakemetadatatypedef)
  - [SourceConnectorPropertiesTypeDef](#sourceconnectorpropertiestypedef)
  - [SourceFieldPropertiesTypeDef](#sourcefieldpropertiestypedef)
  - [SourceFlowConfigTypeDef](#sourceflowconfigtypedef)
  - [StartFlowRequestRequestTypeDef](#startflowrequestrequesttypedef)
  - [StartFlowResponseTypeDef](#startflowresponsetypedef)
  - [StopFlowRequestRequestTypeDef](#stopflowrequestrequesttypedef)
  - [StopFlowResponseTypeDef](#stopflowresponsetypedef)
  - [SupportedFieldTypeDetailsTypeDef](#supportedfieldtypedetailstypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TaskTypeDef](#tasktypedef)
  - [TrendmicroConnectorProfileCredentialsTypeDef](#trendmicroconnectorprofilecredentialstypedef)
  - [TrendmicroSourcePropertiesTypeDef](#trendmicrosourcepropertiestypedef)
  - [TriggerConfigTypeDef](#triggerconfigtypedef)
  - [TriggerPropertiesTypeDef](#triggerpropertiestypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateConnectorProfileRequestRequestTypeDef](#updateconnectorprofilerequestrequesttypedef)
  - [UpdateConnectorProfileResponseTypeDef](#updateconnectorprofileresponsetypedef)
  - [UpdateFlowRequestRequestTypeDef](#updateflowrequestrequesttypedef)
  - [UpdateFlowResponseTypeDef](#updateflowresponsetypedef)
  - [UpsolverDestinationPropertiesTypeDef](#upsolverdestinationpropertiestypedef)
  - [UpsolverS3OutputFormatConfigTypeDef](#upsolvers3outputformatconfigtypedef)
  - [VeevaConnectorProfileCredentialsTypeDef](#veevaconnectorprofilecredentialstypedef)
  - [VeevaConnectorProfilePropertiesTypeDef](#veevaconnectorprofilepropertiestypedef)
  - [VeevaSourcePropertiesTypeDef](#veevasourcepropertiestypedef)
  - [ZendeskConnectorProfileCredentialsTypeDef](#zendeskconnectorprofilecredentialstypedef)
  - [ZendeskConnectorProfilePropertiesTypeDef](#zendeskconnectorprofilepropertiestypedef)
  - [ZendeskDestinationPropertiesTypeDef](#zendeskdestinationpropertiestypedef)
  - [ZendeskMetadataTypeDef](#zendeskmetadatatypedef)
  - [ZendeskSourcePropertiesTypeDef](#zendesksourcepropertiestypedef)

<a id="aggregationconfigtypedef"></a>

## AggregationConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import AggregationConfigTypeDef
```

Optional fields:

- `aggregationType`: [AggregationTypeType](./literals.md#aggregationtypetype)

<a id="amplitudeconnectorprofilecredentialstypedef"></a>

## AmplitudeConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import AmplitudeConnectorProfileCredentialsTypeDef
```

Required fields:

- `apiKey`: `str`
- `secretKey`: `str`

<a id="amplitudesourcepropertiestypedef"></a>

## AmplitudeSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import AmplitudeSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="basicauthcredentialstypedef"></a>

## BasicAuthCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import BasicAuthCredentialsTypeDef
```

Required fields:

- `username`: `str`
- `password`: `str`

<a id="connectorconfigurationtypedef"></a>

## ConnectorConfigurationTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorConfigurationTypeDef
```

Optional fields:

- `canUseAsSource`: `bool`
- `canUseAsDestination`: `bool`
- `supportedDestinationConnectors`:
  `List`\[[ConnectorTypeType](./literals.md#connectortypetype)\]
- `supportedSchedulingFrequencies`:
  `List`\[[ScheduleFrequencyTypeType](./literals.md#schedulefrequencytypetype)\]
- `isPrivateLinkEnabled`: `bool`
- `isPrivateLinkEndpointUrlRequired`: `bool`
- `supportedTriggerTypes`:
  `List`\[[TriggerTypeType](./literals.md#triggertypetype)\]
- `connectorMetadata`:
  [ConnectorMetadataTypeDef](./type_defs.md#connectormetadatatypedef)

<a id="connectorentityfieldtypedef"></a>

## ConnectorEntityFieldTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorEntityFieldTypeDef
```

Required fields:

- `identifier`: `str`

Optional fields:

- `label`: `str`
- `supportedFieldTypeDetails`:
  [SupportedFieldTypeDetailsTypeDef](./type_defs.md#supportedfieldtypedetailstypedef)
- `description`: `str`
- `sourceProperties`:
  [SourceFieldPropertiesTypeDef](./type_defs.md#sourcefieldpropertiestypedef)
- `destinationProperties`:
  [DestinationFieldPropertiesTypeDef](./type_defs.md#destinationfieldpropertiestypedef)

<a id="connectorentitytypedef"></a>

## ConnectorEntityTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorEntityTypeDef
```

Required fields:

- `name`: `str`

Optional fields:

- `label`: `str`
- `hasNestedEntities`: `bool`

<a id="connectormetadatatypedef"></a>

## ConnectorMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorMetadataTypeDef
```

Optional fields:

- `Amplitude`: `Dict`\[`str`, `Any`\]
- `Datadog`: `Dict`\[`str`, `Any`\]
- `Dynatrace`: `Dict`\[`str`, `Any`\]
- `GoogleAnalytics`:
  [GoogleAnalyticsMetadataTypeDef](./type_defs.md#googleanalyticsmetadatatypedef)
- `InforNexus`: `Dict`\[`str`, `Any`\]
- `Marketo`: `Dict`\[`str`, `Any`\]
- `Redshift`: `Dict`\[`str`, `Any`\]
- `S3`: `Dict`\[`str`, `Any`\]
- `Salesforce`:
  [SalesforceMetadataTypeDef](./type_defs.md#salesforcemetadatatypedef)
- `ServiceNow`: `Dict`\[`str`, `Any`\]
- `Singular`: `Dict`\[`str`, `Any`\]
- `Slack`: [SlackMetadataTypeDef](./type_defs.md#slackmetadatatypedef)
- `Snowflake`:
  [SnowflakeMetadataTypeDef](./type_defs.md#snowflakemetadatatypedef)
- `Trendmicro`: `Dict`\[`str`, `Any`\]
- `Veeva`: `Dict`\[`str`, `Any`\]
- `Zendesk`: [ZendeskMetadataTypeDef](./type_defs.md#zendeskmetadatatypedef)
- `EventBridge`: `Dict`\[`str`, `Any`\]
- `Upsolver`: `Dict`\[`str`, `Any`\]
- `CustomerProfiles`: `Dict`\[`str`, `Any`\]
- `Honeycode`:
  [HoneycodeMetadataTypeDef](./type_defs.md#honeycodemetadatatypedef)
- `SAPOData`: `Dict`\[`str`, `Any`\]

<a id="connectoroauthrequesttypedef"></a>

## ConnectorOAuthRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorOAuthRequestTypeDef
```

Optional fields:

- `authCode`: `str`
- `redirectUri`: `str`

<a id="connectoroperatortypedef"></a>

## ConnectorOperatorTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorOperatorTypeDef
```

Optional fields:

- `Amplitude`: `Literal['BETWEEN']` (see
  [AmplitudeConnectorOperatorType](./literals.md#amplitudeconnectoroperatortype))
- `Datadog`:
  [DatadogConnectorOperatorType](./literals.md#datadogconnectoroperatortype)
- `Dynatrace`:
  [DynatraceConnectorOperatorType](./literals.md#dynatraceconnectoroperatortype)
- `GoogleAnalytics`:
  [GoogleAnalyticsConnectorOperatorType](./literals.md#googleanalyticsconnectoroperatortype)
- `InforNexus`:
  [InforNexusConnectorOperatorType](./literals.md#infornexusconnectoroperatortype)
- `Marketo`:
  [MarketoConnectorOperatorType](./literals.md#marketoconnectoroperatortype)
- `S3`: [S3ConnectorOperatorType](./literals.md#s3connectoroperatortype)
- `Salesforce`:
  [SalesforceConnectorOperatorType](./literals.md#salesforceconnectoroperatortype)
- `ServiceNow`:
  [ServiceNowConnectorOperatorType](./literals.md#servicenowconnectoroperatortype)
- `Singular`:
  [SingularConnectorOperatorType](./literals.md#singularconnectoroperatortype)
- `Slack`:
  [SlackConnectorOperatorType](./literals.md#slackconnectoroperatortype)
- `Trendmicro`:
  [TrendmicroConnectorOperatorType](./literals.md#trendmicroconnectoroperatortype)
- `Veeva`:
  [VeevaConnectorOperatorType](./literals.md#veevaconnectoroperatortype)
- `Zendesk`:
  [ZendeskConnectorOperatorType](./literals.md#zendeskconnectoroperatortype)
- `SAPOData`:
  [SAPODataConnectorOperatorType](./literals.md#sapodataconnectoroperatortype)

<a id="connectorprofileconfigtypedef"></a>

## ConnectorProfileConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorProfileConfigTypeDef
```

Required fields:

- `connectorProfileProperties`:
  [ConnectorProfilePropertiesTypeDef](./type_defs.md#connectorprofilepropertiestypedef)
- `connectorProfileCredentials`:
  [ConnectorProfileCredentialsTypeDef](./type_defs.md#connectorprofilecredentialstypedef)

<a id="connectorprofilecredentialstypedef"></a>

## ConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorProfileCredentialsTypeDef
```

Optional fields:

- `Amplitude`:
  [AmplitudeConnectorProfileCredentialsTypeDef](./type_defs.md#amplitudeconnectorprofilecredentialstypedef)
- `Datadog`:
  [DatadogConnectorProfileCredentialsTypeDef](./type_defs.md#datadogconnectorprofilecredentialstypedef)
- `Dynatrace`:
  [DynatraceConnectorProfileCredentialsTypeDef](./type_defs.md#dynatraceconnectorprofilecredentialstypedef)
- `GoogleAnalytics`:
  [GoogleAnalyticsConnectorProfileCredentialsTypeDef](./type_defs.md#googleanalyticsconnectorprofilecredentialstypedef)
- `Honeycode`:
  [HoneycodeConnectorProfileCredentialsTypeDef](./type_defs.md#honeycodeconnectorprofilecredentialstypedef)
- `InforNexus`:
  [InforNexusConnectorProfileCredentialsTypeDef](./type_defs.md#infornexusconnectorprofilecredentialstypedef)
- `Marketo`:
  [MarketoConnectorProfileCredentialsTypeDef](./type_defs.md#marketoconnectorprofilecredentialstypedef)
- `Redshift`:
  [RedshiftConnectorProfileCredentialsTypeDef](./type_defs.md#redshiftconnectorprofilecredentialstypedef)
- `Salesforce`:
  [SalesforceConnectorProfileCredentialsTypeDef](./type_defs.md#salesforceconnectorprofilecredentialstypedef)
- `ServiceNow`:
  [ServiceNowConnectorProfileCredentialsTypeDef](./type_defs.md#servicenowconnectorprofilecredentialstypedef)
- `Singular`:
  [SingularConnectorProfileCredentialsTypeDef](./type_defs.md#singularconnectorprofilecredentialstypedef)
- `Slack`:
  [SlackConnectorProfileCredentialsTypeDef](./type_defs.md#slackconnectorprofilecredentialstypedef)
- `Snowflake`:
  [SnowflakeConnectorProfileCredentialsTypeDef](./type_defs.md#snowflakeconnectorprofilecredentialstypedef)
- `Trendmicro`:
  [TrendmicroConnectorProfileCredentialsTypeDef](./type_defs.md#trendmicroconnectorprofilecredentialstypedef)
- `Veeva`:
  [VeevaConnectorProfileCredentialsTypeDef](./type_defs.md#veevaconnectorprofilecredentialstypedef)
- `Zendesk`:
  [ZendeskConnectorProfileCredentialsTypeDef](./type_defs.md#zendeskconnectorprofilecredentialstypedef)
- `SAPOData`:
  [SAPODataConnectorProfileCredentialsTypeDef](./type_defs.md#sapodataconnectorprofilecredentialstypedef)

<a id="connectorprofilepropertiestypedef"></a>

## ConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorProfilePropertiesTypeDef
```

Optional fields:

- `Amplitude`: `Mapping`\[`str`, `Any`\]
- `Datadog`:
  [DatadogConnectorProfilePropertiesTypeDef](./type_defs.md#datadogconnectorprofilepropertiestypedef)
- `Dynatrace`:
  [DynatraceConnectorProfilePropertiesTypeDef](./type_defs.md#dynatraceconnectorprofilepropertiestypedef)
- `GoogleAnalytics`: `Mapping`\[`str`, `Any`\]
- `Honeycode`: `Mapping`\[`str`, `Any`\]
- `InforNexus`:
  [InforNexusConnectorProfilePropertiesTypeDef](./type_defs.md#infornexusconnectorprofilepropertiestypedef)
- `Marketo`:
  [MarketoConnectorProfilePropertiesTypeDef](./type_defs.md#marketoconnectorprofilepropertiestypedef)
- `Redshift`:
  [RedshiftConnectorProfilePropertiesTypeDef](./type_defs.md#redshiftconnectorprofilepropertiestypedef)
- `Salesforce`:
  [SalesforceConnectorProfilePropertiesTypeDef](./type_defs.md#salesforceconnectorprofilepropertiestypedef)
- `ServiceNow`:
  [ServiceNowConnectorProfilePropertiesTypeDef](./type_defs.md#servicenowconnectorprofilepropertiestypedef)
- `Singular`: `Mapping`\[`str`, `Any`\]
- `Slack`:
  [SlackConnectorProfilePropertiesTypeDef](./type_defs.md#slackconnectorprofilepropertiestypedef)
- `Snowflake`:
  [SnowflakeConnectorProfilePropertiesTypeDef](./type_defs.md#snowflakeconnectorprofilepropertiestypedef)
- `Trendmicro`: `Mapping`\[`str`, `Any`\]
- `Veeva`:
  [VeevaConnectorProfilePropertiesTypeDef](./type_defs.md#veevaconnectorprofilepropertiestypedef)
- `Zendesk`:
  [ZendeskConnectorProfilePropertiesTypeDef](./type_defs.md#zendeskconnectorprofilepropertiestypedef)
- `SAPOData`:
  [SAPODataConnectorProfilePropertiesTypeDef](./type_defs.md#sapodataconnectorprofilepropertiestypedef)

<a id="connectorprofiletypedef"></a>

## ConnectorProfileTypeDef

```python
from types_aiobotocore_appflow.type_defs import ConnectorProfileTypeDef
```

Optional fields:

- `connectorProfileArn`: `str`
- `connectorProfileName`: `str`
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `connectionMode`: [ConnectionModeType](./literals.md#connectionmodetype)
- `credentialsArn`: `str`
- `connectorProfileProperties`:
  [ConnectorProfilePropertiesTypeDef](./type_defs.md#connectorprofilepropertiestypedef)
- `createdAt`: `datetime`
- `lastUpdatedAt`: `datetime`
- `privateConnectionProvisioningState`:
  [PrivateConnectionProvisioningStateTypeDef](./type_defs.md#privateconnectionprovisioningstatetypedef)

<a id="createconnectorprofilerequestrequesttypedef"></a>

## CreateConnectorProfileRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import CreateConnectorProfileRequestRequestTypeDef
```

Required fields:

- `connectorProfileName`: `str`
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `connectionMode`: [ConnectionModeType](./literals.md#connectionmodetype)
- `connectorProfileConfig`:
  [ConnectorProfileConfigTypeDef](./type_defs.md#connectorprofileconfigtypedef)

Optional fields:

- `kmsArn`: `str`

<a id="createconnectorprofileresponsetypedef"></a>

## CreateConnectorProfileResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import CreateConnectorProfileResponseTypeDef
```

Required fields:

- `connectorProfileArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createflowrequestrequesttypedef"></a>

## CreateFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import CreateFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`
- `triggerConfig`: [TriggerConfigTypeDef](./type_defs.md#triggerconfigtypedef)
- `sourceFlowConfig`:
  [SourceFlowConfigTypeDef](./type_defs.md#sourceflowconfigtypedef)
- `destinationFlowConfigList`:
  `Sequence`\[[DestinationFlowConfigTypeDef](./type_defs.md#destinationflowconfigtypedef)\]
- `tasks`: `Sequence`\[[TaskTypeDef](./type_defs.md#tasktypedef)\]

Optional fields:

- `description`: `str`
- `kmsArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="createflowresponsetypedef"></a>

## CreateFlowResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import CreateFlowResponseTypeDef
```

Required fields:

- `flowArn`: `str`
- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="customerprofilesdestinationpropertiestypedef"></a>

## CustomerProfilesDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import CustomerProfilesDestinationPropertiesTypeDef
```

Required fields:

- `domainName`: `str`

Optional fields:

- `objectTypeName`: `str`

<a id="datadogconnectorprofilecredentialstypedef"></a>

## DatadogConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import DatadogConnectorProfileCredentialsTypeDef
```

Required fields:

- `apiKey`: `str`
- `applicationKey`: `str`

<a id="datadogconnectorprofilepropertiestypedef"></a>

## DatadogConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DatadogConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="datadogsourcepropertiestypedef"></a>

## DatadogSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DatadogSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="deleteconnectorprofilerequestrequesttypedef"></a>

## DeleteConnectorProfileRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DeleteConnectorProfileRequestRequestTypeDef
```

Required fields:

- `connectorProfileName`: `str`

Optional fields:

- `forceDelete`: `bool`

<a id="deleteflowrequestrequesttypedef"></a>

## DeleteFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DeleteFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`

Optional fields:

- `forceDelete`: `bool`

<a id="describeconnectorentityrequestrequesttypedef"></a>

## DescribeConnectorEntityRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorEntityRequestRequestTypeDef
```

Required fields:

- `connectorEntityName`: `str`

Optional fields:

- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `connectorProfileName`: `str`

<a id="describeconnectorentityresponsetypedef"></a>

## DescribeConnectorEntityResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorEntityResponseTypeDef
```

Required fields:

- `connectorEntityFields`:
  `List`\[[ConnectorEntityFieldTypeDef](./type_defs.md#connectorentityfieldtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeconnectorprofilesrequestrequesttypedef"></a>

## DescribeConnectorProfilesRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorProfilesRequestRequestTypeDef
```

Optional fields:

- `connectorProfileNames`: `Sequence`\[`str`\]
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `maxResults`: `int`
- `nextToken`: `str`

<a id="describeconnectorprofilesresponsetypedef"></a>

## DescribeConnectorProfilesResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorProfilesResponseTypeDef
```

Required fields:

- `connectorProfileDetails`:
  `List`\[[ConnectorProfileTypeDef](./type_defs.md#connectorprofiletypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeconnectorsrequestrequesttypedef"></a>

## DescribeConnectorsRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorsRequestRequestTypeDef
```

Optional fields:

- `connectorTypes`:
  `Sequence`\[[ConnectorTypeType](./literals.md#connectortypetype)\]
- `nextToken`: `str`

<a id="describeconnectorsresponsetypedef"></a>

## DescribeConnectorsResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeConnectorsResponseTypeDef
```

Required fields:

- `connectorConfigurations`:
  `Dict`\[[ConnectorTypeType](./literals.md#connectortypetype),
  [ConnectorConfigurationTypeDef](./type_defs.md#connectorconfigurationtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeflowexecutionrecordsrequestrequesttypedef"></a>

## DescribeFlowExecutionRecordsRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeFlowExecutionRecordsRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="describeflowexecutionrecordsresponsetypedef"></a>

## DescribeFlowExecutionRecordsResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeFlowExecutionRecordsResponseTypeDef
```

Required fields:

- `flowExecutions`:
  `List`\[[ExecutionRecordTypeDef](./type_defs.md#executionrecordtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeflowrequestrequesttypedef"></a>

## DescribeFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`

<a id="describeflowresponsetypedef"></a>

## DescribeFlowResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import DescribeFlowResponseTypeDef
```

Required fields:

- `flowArn`: `str`
- `description`: `str`
- `flowName`: `str`
- `kmsArn`: `str`
- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `flowStatusMessage`: `str`
- `sourceFlowConfig`:
  [SourceFlowConfigTypeDef](./type_defs.md#sourceflowconfigtypedef)
- `destinationFlowConfigList`:
  `List`\[[DestinationFlowConfigTypeDef](./type_defs.md#destinationflowconfigtypedef)\]
- `lastRunExecutionDetails`:
  [ExecutionDetailsTypeDef](./type_defs.md#executiondetailstypedef)
- `triggerConfig`: [TriggerConfigTypeDef](./type_defs.md#triggerconfigtypedef)
- `tasks`: `List`\[[TaskTypeDef](./type_defs.md#tasktypedef)\]
- `createdAt`: `datetime`
- `lastUpdatedAt`: `datetime`
- `createdBy`: `str`
- `lastUpdatedBy`: `str`
- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="destinationconnectorpropertiestypedef"></a>

## DestinationConnectorPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DestinationConnectorPropertiesTypeDef
```

Optional fields:

- `Redshift`:
  [RedshiftDestinationPropertiesTypeDef](./type_defs.md#redshiftdestinationpropertiestypedef)
- `S3`:
  [S3DestinationPropertiesTypeDef](./type_defs.md#s3destinationpropertiestypedef)
- `Salesforce`:
  [SalesforceDestinationPropertiesTypeDef](./type_defs.md#salesforcedestinationpropertiestypedef)
- `Snowflake`:
  [SnowflakeDestinationPropertiesTypeDef](./type_defs.md#snowflakedestinationpropertiestypedef)
- `EventBridge`:
  [EventBridgeDestinationPropertiesTypeDef](./type_defs.md#eventbridgedestinationpropertiestypedef)
- `LookoutMetrics`: `Mapping`\[`str`, `Any`\]
- `Upsolver`:
  [UpsolverDestinationPropertiesTypeDef](./type_defs.md#upsolverdestinationpropertiestypedef)
- `Honeycode`:
  [HoneycodeDestinationPropertiesTypeDef](./type_defs.md#honeycodedestinationpropertiestypedef)
- `CustomerProfiles`:
  [CustomerProfilesDestinationPropertiesTypeDef](./type_defs.md#customerprofilesdestinationpropertiestypedef)
- `Zendesk`:
  [ZendeskDestinationPropertiesTypeDef](./type_defs.md#zendeskdestinationpropertiestypedef)

<a id="destinationfieldpropertiestypedef"></a>

## DestinationFieldPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DestinationFieldPropertiesTypeDef
```

Optional fields:

- `isCreatable`: `bool`
- `isNullable`: `bool`
- `isUpsertable`: `bool`
- `isUpdatable`: `bool`
- `supportedWriteOperations`:
  `List`\[[WriteOperationTypeType](./literals.md#writeoperationtypetype)\]

<a id="destinationflowconfigtypedef"></a>

## DestinationFlowConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import DestinationFlowConfigTypeDef
```

Required fields:

- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `destinationConnectorProperties`:
  [DestinationConnectorPropertiesTypeDef](./type_defs.md#destinationconnectorpropertiestypedef)

Optional fields:

- `connectorProfileName`: `str`

<a id="dynatraceconnectorprofilecredentialstypedef"></a>

## DynatraceConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import DynatraceConnectorProfileCredentialsTypeDef
```

Required fields:

- `apiToken`: `str`

<a id="dynatraceconnectorprofilepropertiestypedef"></a>

## DynatraceConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DynatraceConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="dynatracesourcepropertiestypedef"></a>

## DynatraceSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import DynatraceSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="errorhandlingconfigtypedef"></a>

## ErrorHandlingConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import ErrorHandlingConfigTypeDef
```

Optional fields:

- `failOnFirstDestinationError`: `bool`
- `bucketPrefix`: `str`
- `bucketName`: `str`

<a id="errorinfotypedef"></a>

## ErrorInfoTypeDef

```python
from types_aiobotocore_appflow.type_defs import ErrorInfoTypeDef
```

Optional fields:

- `putFailuresCount`: `int`
- `executionMessage`: `str`

<a id="eventbridgedestinationpropertiestypedef"></a>

## EventBridgeDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import EventBridgeDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)

<a id="executiondetailstypedef"></a>

## ExecutionDetailsTypeDef

```python
from types_aiobotocore_appflow.type_defs import ExecutionDetailsTypeDef
```

Optional fields:

- `mostRecentExecutionMessage`: `str`
- `mostRecentExecutionTime`: `datetime`
- `mostRecentExecutionStatus`:
  [ExecutionStatusType](./literals.md#executionstatustype)

<a id="executionrecordtypedef"></a>

## ExecutionRecordTypeDef

```python
from types_aiobotocore_appflow.type_defs import ExecutionRecordTypeDef
```

Optional fields:

- `executionId`: `str`
- `executionStatus`: [ExecutionStatusType](./literals.md#executionstatustype)
- `executionResult`:
  [ExecutionResultTypeDef](./type_defs.md#executionresulttypedef)
- `startedAt`: `datetime`
- `lastUpdatedAt`: `datetime`
- `dataPullStartTime`: `datetime`
- `dataPullEndTime`: `datetime`

<a id="executionresulttypedef"></a>

## ExecutionResultTypeDef

```python
from types_aiobotocore_appflow.type_defs import ExecutionResultTypeDef
```

Optional fields:

- `errorInfo`: [ErrorInfoTypeDef](./type_defs.md#errorinfotypedef)
- `bytesProcessed`: `int`
- `bytesWritten`: `int`
- `recordsProcessed`: `int`

<a id="fieldtypedetailstypedef"></a>

## FieldTypeDetailsTypeDef

```python
from types_aiobotocore_appflow.type_defs import FieldTypeDetailsTypeDef
```

Required fields:

- `fieldType`: `str`
- `filterOperators`: `List`\[[OperatorType](./literals.md#operatortype)\]

Optional fields:

- `supportedValues`: `List`\[`str`\]

<a id="flowdefinitiontypedef"></a>

## FlowDefinitionTypeDef

```python
from types_aiobotocore_appflow.type_defs import FlowDefinitionTypeDef
```

Optional fields:

- `flowArn`: `str`
- `description`: `str`
- `flowName`: `str`
- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `sourceConnectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `destinationConnectorType`:
  [ConnectorTypeType](./literals.md#connectortypetype)
- `triggerType`: [TriggerTypeType](./literals.md#triggertypetype)
- `createdAt`: `datetime`
- `lastUpdatedAt`: `datetime`
- `createdBy`: `str`
- `lastUpdatedBy`: `str`
- `tags`: `Dict`\[`str`, `str`\]
- `lastRunExecutionDetails`:
  [ExecutionDetailsTypeDef](./type_defs.md#executiondetailstypedef)

<a id="googleanalyticsconnectorprofilecredentialstypedef"></a>

## GoogleAnalyticsConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import GoogleAnalyticsConnectorProfileCredentialsTypeDef
```

Required fields:

- `clientId`: `str`
- `clientSecret`: `str`

Optional fields:

- `accessToken`: `str`
- `refreshToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="googleanalyticsmetadatatypedef"></a>

## GoogleAnalyticsMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import GoogleAnalyticsMetadataTypeDef
```

Optional fields:

- `oAuthScopes`: `List`\[`str`\]

<a id="googleanalyticssourcepropertiestypedef"></a>

## GoogleAnalyticsSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import GoogleAnalyticsSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="honeycodeconnectorprofilecredentialstypedef"></a>

## HoneycodeConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import HoneycodeConnectorProfileCredentialsTypeDef
```

Optional fields:

- `accessToken`: `str`
- `refreshToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="honeycodedestinationpropertiestypedef"></a>

## HoneycodeDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import HoneycodeDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)

<a id="honeycodemetadatatypedef"></a>

## HoneycodeMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import HoneycodeMetadataTypeDef
```

Optional fields:

- `oAuthScopes`: `List`\[`str`\]

<a id="incrementalpullconfigtypedef"></a>

## IncrementalPullConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import IncrementalPullConfigTypeDef
```

Optional fields:

- `datetimeTypeFieldName`: `str`

<a id="infornexusconnectorprofilecredentialstypedef"></a>

## InforNexusConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import InforNexusConnectorProfileCredentialsTypeDef
```

Required fields:

- `accessKeyId`: `str`
- `userId`: `str`
- `secretAccessKey`: `str`
- `datakey`: `str`

<a id="infornexusconnectorprofilepropertiestypedef"></a>

## InforNexusConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import InforNexusConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="infornexussourcepropertiestypedef"></a>

## InforNexusSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import InforNexusSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="listconnectorentitiesrequestrequesttypedef"></a>

## ListConnectorEntitiesRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListConnectorEntitiesRequestRequestTypeDef
```

Optional fields:

- `connectorProfileName`: `str`
- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `entitiesPath`: `str`

<a id="listconnectorentitiesresponsetypedef"></a>

## ListConnectorEntitiesResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListConnectorEntitiesResponseTypeDef
```

Required fields:

- `connectorEntityMap`: `Dict`\[`str`,
  `List`\[[ConnectorEntityTypeDef](./type_defs.md#connectorentitytypedef)\]\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listflowsrequestrequesttypedef"></a>

## ListFlowsRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListFlowsRequestRequestTypeDef
```

Optional fields:

- `maxResults`: `int`
- `nextToken`: `str`

<a id="listflowsresponsetypedef"></a>

## ListFlowsResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListFlowsResponseTypeDef
```

Required fields:

- `flows`:
  `List`\[[FlowDefinitionTypeDef](./type_defs.md#flowdefinitiontypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `tags`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="marketoconnectorprofilecredentialstypedef"></a>

## MarketoConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import MarketoConnectorProfileCredentialsTypeDef
```

Required fields:

- `clientId`: `str`
- `clientSecret`: `str`

Optional fields:

- `accessToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="marketoconnectorprofilepropertiestypedef"></a>

## MarketoConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import MarketoConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="marketosourcepropertiestypedef"></a>

## MarketoSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import MarketoSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="oauthcredentialstypedef"></a>

## OAuthCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import OAuthCredentialsTypeDef
```

Required fields:

- `clientId`: `str`
- `clientSecret`: `str`

Optional fields:

- `accessToken`: `str`
- `refreshToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="oauthpropertiestypedef"></a>

## OAuthPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import OAuthPropertiesTypeDef
```

Required fields:

- `tokenUrl`: `str`
- `authCodeUrl`: `str`
- `oAuthScopes`: `Sequence`\[`str`\]

<a id="prefixconfigtypedef"></a>

## PrefixConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import PrefixConfigTypeDef
```

Optional fields:

- `prefixType`: [PrefixTypeType](./literals.md#prefixtypetype)
- `prefixFormat`: [PrefixFormatType](./literals.md#prefixformattype)

<a id="privateconnectionprovisioningstatetypedef"></a>

## PrivateConnectionProvisioningStateTypeDef

```python
from types_aiobotocore_appflow.type_defs import PrivateConnectionProvisioningStateTypeDef
```

Optional fields:

- `status`:
  [PrivateConnectionProvisioningStatusType](./literals.md#privateconnectionprovisioningstatustype)
- `failureMessage`: `str`
- `failureCause`:
  [PrivateConnectionProvisioningFailureCauseType](./literals.md#privateconnectionprovisioningfailurecausetype)

<a id="redshiftconnectorprofilecredentialstypedef"></a>

## RedshiftConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import RedshiftConnectorProfileCredentialsTypeDef
```

Required fields:

- `username`: `str`
- `password`: `str`

<a id="redshiftconnectorprofilepropertiestypedef"></a>

## RedshiftConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import RedshiftConnectorProfilePropertiesTypeDef
```

Required fields:

- `databaseUrl`: `str`
- `bucketName`: `str`
- `roleArn`: `str`

Optional fields:

- `bucketPrefix`: `str`

<a id="redshiftdestinationpropertiestypedef"></a>

## RedshiftDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import RedshiftDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`
- `intermediateBucketName`: `str`

Optional fields:

- `bucketPrefix`: `str`
- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3destinationpropertiestypedef"></a>

## S3DestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import S3DestinationPropertiesTypeDef
```

Required fields:

- `bucketName`: `str`

Optional fields:

- `bucketPrefix`: `str`
- `s3OutputFormatConfig`:
  [S3OutputFormatConfigTypeDef](./type_defs.md#s3outputformatconfigtypedef)

<a id="s3inputformatconfigtypedef"></a>

## S3InputFormatConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import S3InputFormatConfigTypeDef
```

Optional fields:

- `s3InputFileType`: [S3InputFileTypeType](./literals.md#s3inputfiletypetype)

<a id="s3outputformatconfigtypedef"></a>

## S3OutputFormatConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import S3OutputFormatConfigTypeDef
```

Optional fields:

- `fileType`: [FileTypeType](./literals.md#filetypetype)
- `prefixConfig`: [PrefixConfigTypeDef](./type_defs.md#prefixconfigtypedef)
- `aggregationConfig`:
  [AggregationConfigTypeDef](./type_defs.md#aggregationconfigtypedef)

<a id="s3sourcepropertiestypedef"></a>

## S3SourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import S3SourcePropertiesTypeDef
```

Required fields:

- `bucketName`: `str`

Optional fields:

- `bucketPrefix`: `str`
- `s3InputFormatConfig`:
  [S3InputFormatConfigTypeDef](./type_defs.md#s3inputformatconfigtypedef)

<a id="sapodataconnectorprofilecredentialstypedef"></a>

## SAPODataConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SAPODataConnectorProfileCredentialsTypeDef
```

Optional fields:

- `basicAuthCredentials`:
  [BasicAuthCredentialsTypeDef](./type_defs.md#basicauthcredentialstypedef)
- `oAuthCredentials`:
  [OAuthCredentialsTypeDef](./type_defs.md#oauthcredentialstypedef)

<a id="sapodataconnectorprofilepropertiestypedef"></a>

## SAPODataConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SAPODataConnectorProfilePropertiesTypeDef
```

Required fields:

- `applicationHostUrl`: `str`
- `applicationServicePath`: `str`
- `portNumber`: `int`
- `clientNumber`: `str`

Optional fields:

- `logonLanguage`: `str`
- `privateLinkServiceName`: `str`
- `oAuthProperties`:
  [OAuthPropertiesTypeDef](./type_defs.md#oauthpropertiestypedef)

<a id="sapodatasourcepropertiestypedef"></a>

## SAPODataSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SAPODataSourcePropertiesTypeDef
```

Optional fields:

- `objectPath`: `str`

<a id="salesforceconnectorprofilecredentialstypedef"></a>

## SalesforceConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SalesforceConnectorProfileCredentialsTypeDef
```

Optional fields:

- `accessToken`: `str`
- `refreshToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)
- `clientCredentialsArn`: `str`

<a id="salesforceconnectorprofilepropertiestypedef"></a>

## SalesforceConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SalesforceConnectorProfilePropertiesTypeDef
```

Optional fields:

- `instanceUrl`: `str`
- `isSandboxEnvironment`: `bool`

<a id="salesforcedestinationpropertiestypedef"></a>

## SalesforceDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SalesforceDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `idFieldNames`: `Sequence`\[`str`\]
- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)
- `writeOperationType`:
  [WriteOperationTypeType](./literals.md#writeoperationtypetype)

<a id="salesforcemetadatatypedef"></a>

## SalesforceMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import SalesforceMetadataTypeDef
```

Optional fields:

- `oAuthScopes`: `List`\[`str`\]

<a id="salesforcesourcepropertiestypedef"></a>

## SalesforceSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SalesforceSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `enableDynamicFieldUpdate`: `bool`
- `includeDeletedRecords`: `bool`

<a id="scheduledtriggerpropertiestypedef"></a>

## ScheduledTriggerPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ScheduledTriggerPropertiesTypeDef
```

Required fields:

- `scheduleExpression`: `str`

Optional fields:

- `dataPullMode`: [DataPullModeType](./literals.md#datapullmodetype)
- `scheduleStartTime`: `Union`\[`datetime`, `str`\]
- `scheduleEndTime`: `Union`\[`datetime`, `str`\]
- `timezone`: `str`
- `scheduleOffset`: `int`
- `firstExecutionFrom`: `Union`\[`datetime`, `str`\]

<a id="servicenowconnectorprofilecredentialstypedef"></a>

## ServiceNowConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import ServiceNowConnectorProfileCredentialsTypeDef
```

Required fields:

- `username`: `str`
- `password`: `str`

<a id="servicenowconnectorprofilepropertiestypedef"></a>

## ServiceNowConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ServiceNowConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="servicenowsourcepropertiestypedef"></a>

## ServiceNowSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ServiceNowSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="singularconnectorprofilecredentialstypedef"></a>

## SingularConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SingularConnectorProfileCredentialsTypeDef
```

Required fields:

- `apiKey`: `str`

<a id="singularsourcepropertiestypedef"></a>

## SingularSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SingularSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="slackconnectorprofilecredentialstypedef"></a>

## SlackConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SlackConnectorProfileCredentialsTypeDef
```

Required fields:

- `clientId`: `str`
- `clientSecret`: `str`

Optional fields:

- `accessToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="slackconnectorprofilepropertiestypedef"></a>

## SlackConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SlackConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="slackmetadatatypedef"></a>

## SlackMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import SlackMetadataTypeDef
```

Optional fields:

- `oAuthScopes`: `List`\[`str`\]

<a id="slacksourcepropertiestypedef"></a>

## SlackSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SlackSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="snowflakeconnectorprofilecredentialstypedef"></a>

## SnowflakeConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SnowflakeConnectorProfileCredentialsTypeDef
```

Required fields:

- `username`: `str`
- `password`: `str`

<a id="snowflakeconnectorprofilepropertiestypedef"></a>

## SnowflakeConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SnowflakeConnectorProfilePropertiesTypeDef
```

Required fields:

- `warehouse`: `str`
- `stage`: `str`
- `bucketName`: `str`

Optional fields:

- `bucketPrefix`: `str`
- `privateLinkServiceName`: `str`
- `accountName`: `str`
- `region`: `str`

<a id="snowflakedestinationpropertiestypedef"></a>

## SnowflakeDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SnowflakeDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`
- `intermediateBucketName`: `str`

Optional fields:

- `bucketPrefix`: `str`
- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)

<a id="snowflakemetadatatypedef"></a>

## SnowflakeMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import SnowflakeMetadataTypeDef
```

Optional fields:

- `supportedRegions`: `List`\[`str`\]

<a id="sourceconnectorpropertiestypedef"></a>

## SourceConnectorPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SourceConnectorPropertiesTypeDef
```

Optional fields:

- `Amplitude`:
  [AmplitudeSourcePropertiesTypeDef](./type_defs.md#amplitudesourcepropertiestypedef)
- `Datadog`:
  [DatadogSourcePropertiesTypeDef](./type_defs.md#datadogsourcepropertiestypedef)
- `Dynatrace`:
  [DynatraceSourcePropertiesTypeDef](./type_defs.md#dynatracesourcepropertiestypedef)
- `GoogleAnalytics`:
  [GoogleAnalyticsSourcePropertiesTypeDef](./type_defs.md#googleanalyticssourcepropertiestypedef)
- `InforNexus`:
  [InforNexusSourcePropertiesTypeDef](./type_defs.md#infornexussourcepropertiestypedef)
- `Marketo`:
  [MarketoSourcePropertiesTypeDef](./type_defs.md#marketosourcepropertiestypedef)
- `S3`: [S3SourcePropertiesTypeDef](./type_defs.md#s3sourcepropertiestypedef)
- `Salesforce`:
  [SalesforceSourcePropertiesTypeDef](./type_defs.md#salesforcesourcepropertiestypedef)
- `ServiceNow`:
  [ServiceNowSourcePropertiesTypeDef](./type_defs.md#servicenowsourcepropertiestypedef)
- `Singular`:
  [SingularSourcePropertiesTypeDef](./type_defs.md#singularsourcepropertiestypedef)
- `Slack`:
  [SlackSourcePropertiesTypeDef](./type_defs.md#slacksourcepropertiestypedef)
- `Trendmicro`:
  [TrendmicroSourcePropertiesTypeDef](./type_defs.md#trendmicrosourcepropertiestypedef)
- `Veeva`:
  [VeevaSourcePropertiesTypeDef](./type_defs.md#veevasourcepropertiestypedef)
- `Zendesk`:
  [ZendeskSourcePropertiesTypeDef](./type_defs.md#zendesksourcepropertiestypedef)
- `SAPOData`:
  [SAPODataSourcePropertiesTypeDef](./type_defs.md#sapodatasourcepropertiestypedef)

<a id="sourcefieldpropertiestypedef"></a>

## SourceFieldPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import SourceFieldPropertiesTypeDef
```

Optional fields:

- `isRetrievable`: `bool`
- `isQueryable`: `bool`

<a id="sourceflowconfigtypedef"></a>

## SourceFlowConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import SourceFlowConfigTypeDef
```

Required fields:

- `connectorType`: [ConnectorTypeType](./literals.md#connectortypetype)
- `sourceConnectorProperties`:
  [SourceConnectorPropertiesTypeDef](./type_defs.md#sourceconnectorpropertiestypedef)

Optional fields:

- `connectorProfileName`: `str`
- `incrementalPullConfig`:
  [IncrementalPullConfigTypeDef](./type_defs.md#incrementalpullconfigtypedef)

<a id="startflowrequestrequesttypedef"></a>

## StartFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import StartFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`

<a id="startflowresponsetypedef"></a>

## StartFlowResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import StartFlowResponseTypeDef
```

Required fields:

- `flowArn`: `str`
- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `executionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopflowrequestrequesttypedef"></a>

## StopFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import StopFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`

<a id="stopflowresponsetypedef"></a>

## StopFlowResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import StopFlowResponseTypeDef
```

Required fields:

- `flowArn`: `str`
- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="supportedfieldtypedetailstypedef"></a>

## SupportedFieldTypeDetailsTypeDef

```python
from types_aiobotocore_appflow.type_defs import SupportedFieldTypeDetailsTypeDef
```

Required fields:

- `v1`: [FieldTypeDetailsTypeDef](./type_defs.md#fieldtypedetailstypedef)

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tags`: `Mapping`\[`str`, `str`\]

<a id="tasktypedef"></a>

## TaskTypeDef

```python
from types_aiobotocore_appflow.type_defs import TaskTypeDef
```

Required fields:

- `sourceFields`: `Sequence`\[`str`\]
- `taskType`: [TaskTypeType](./literals.md#tasktypetype)

Optional fields:

- `connectorOperator`:
  [ConnectorOperatorTypeDef](./type_defs.md#connectoroperatortypedef)
- `destinationField`: `str`
- `taskProperties`:
  `Mapping`\[[OperatorPropertiesKeysType](./literals.md#operatorpropertieskeystype),
  `str`\]

<a id="trendmicroconnectorprofilecredentialstypedef"></a>

## TrendmicroConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import TrendmicroConnectorProfileCredentialsTypeDef
```

Required fields:

- `apiSecretKey`: `str`

<a id="trendmicrosourcepropertiestypedef"></a>

## TrendmicroSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import TrendmicroSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

<a id="triggerconfigtypedef"></a>

## TriggerConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import TriggerConfigTypeDef
```

Required fields:

- `triggerType`: [TriggerTypeType](./literals.md#triggertypetype)

Optional fields:

- `triggerProperties`:
  [TriggerPropertiesTypeDef](./type_defs.md#triggerpropertiestypedef)

<a id="triggerpropertiestypedef"></a>

## TriggerPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import TriggerPropertiesTypeDef
```

Optional fields:

- `Scheduled`:
  [ScheduledTriggerPropertiesTypeDef](./type_defs.md#scheduledtriggerpropertiestypedef)

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceArn`: `str`
- `tagKeys`: `Sequence`\[`str`\]

<a id="updateconnectorprofilerequestrequesttypedef"></a>

## UpdateConnectorProfileRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpdateConnectorProfileRequestRequestTypeDef
```

Required fields:

- `connectorProfileName`: `str`
- `connectionMode`: [ConnectionModeType](./literals.md#connectionmodetype)
- `connectorProfileConfig`:
  [ConnectorProfileConfigTypeDef](./type_defs.md#connectorprofileconfigtypedef)

<a id="updateconnectorprofileresponsetypedef"></a>

## UpdateConnectorProfileResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpdateConnectorProfileResponseTypeDef
```

Required fields:

- `connectorProfileArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateflowrequestrequesttypedef"></a>

## UpdateFlowRequestRequestTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpdateFlowRequestRequestTypeDef
```

Required fields:

- `flowName`: `str`
- `triggerConfig`: [TriggerConfigTypeDef](./type_defs.md#triggerconfigtypedef)
- `sourceFlowConfig`:
  [SourceFlowConfigTypeDef](./type_defs.md#sourceflowconfigtypedef)
- `destinationFlowConfigList`:
  `Sequence`\[[DestinationFlowConfigTypeDef](./type_defs.md#destinationflowconfigtypedef)\]
- `tasks`: `Sequence`\[[TaskTypeDef](./type_defs.md#tasktypedef)\]

Optional fields:

- `description`: `str`

<a id="updateflowresponsetypedef"></a>

## UpdateFlowResponseTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpdateFlowResponseTypeDef
```

Required fields:

- `flowStatus`: [FlowStatusType](./literals.md#flowstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="upsolverdestinationpropertiestypedef"></a>

## UpsolverDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpsolverDestinationPropertiesTypeDef
```

Required fields:

- `bucketName`: `str`
- `s3OutputFormatConfig`:
  [UpsolverS3OutputFormatConfigTypeDef](./type_defs.md#upsolvers3outputformatconfigtypedef)

Optional fields:

- `bucketPrefix`: `str`

<a id="upsolvers3outputformatconfigtypedef"></a>

## UpsolverS3OutputFormatConfigTypeDef

```python
from types_aiobotocore_appflow.type_defs import UpsolverS3OutputFormatConfigTypeDef
```

Required fields:

- `prefixConfig`: [PrefixConfigTypeDef](./type_defs.md#prefixconfigtypedef)

Optional fields:

- `fileType`: [FileTypeType](./literals.md#filetypetype)
- `aggregationConfig`:
  [AggregationConfigTypeDef](./type_defs.md#aggregationconfigtypedef)

<a id="veevaconnectorprofilecredentialstypedef"></a>

## VeevaConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import VeevaConnectorProfileCredentialsTypeDef
```

Required fields:

- `username`: `str`
- `password`: `str`

<a id="veevaconnectorprofilepropertiestypedef"></a>

## VeevaConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import VeevaConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="veevasourcepropertiestypedef"></a>

## VeevaSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import VeevaSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `documentType`: `str`
- `includeSourceFiles`: `bool`
- `includeRenditions`: `bool`
- `includeAllVersions`: `bool`

<a id="zendeskconnectorprofilecredentialstypedef"></a>

## ZendeskConnectorProfileCredentialsTypeDef

```python
from types_aiobotocore_appflow.type_defs import ZendeskConnectorProfileCredentialsTypeDef
```

Required fields:

- `clientId`: `str`
- `clientSecret`: `str`

Optional fields:

- `accessToken`: `str`
- `oAuthRequest`:
  [ConnectorOAuthRequestTypeDef](./type_defs.md#connectoroauthrequesttypedef)

<a id="zendeskconnectorprofilepropertiestypedef"></a>

## ZendeskConnectorProfilePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ZendeskConnectorProfilePropertiesTypeDef
```

Required fields:

- `instanceUrl`: `str`

<a id="zendeskdestinationpropertiestypedef"></a>

## ZendeskDestinationPropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ZendeskDestinationPropertiesTypeDef
```

Required fields:

- `object`: `str`

Optional fields:

- `idFieldNames`: `Sequence`\[`str`\]
- `errorHandlingConfig`:
  [ErrorHandlingConfigTypeDef](./type_defs.md#errorhandlingconfigtypedef)
- `writeOperationType`:
  [WriteOperationTypeType](./literals.md#writeoperationtypetype)

<a id="zendeskmetadatatypedef"></a>

## ZendeskMetadataTypeDef

```python
from types_aiobotocore_appflow.type_defs import ZendeskMetadataTypeDef
```

Optional fields:

- `oAuthScopes`: `List`\[`str`\]

<a id="zendesksourcepropertiestypedef"></a>

## ZendeskSourcePropertiesTypeDef

```python
from types_aiobotocore_appflow.type_defs import ZendeskSourcePropertiesTypeDef
```

Required fields:

- `object`: `str`
