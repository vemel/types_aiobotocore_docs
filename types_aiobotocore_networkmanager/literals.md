<a id="literals-for-aiobotocore-networkmanager-module"></a>

# Literals for aiobotocore NetworkManager module

> [Index](..) > [NetworkManager](.) > Literals

Auto-generated documentation for
[NetworkManager](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/networkmanager.html#NetworkManager)
type annotations stubs module
[types-aiobotocore-networkmanager](https://pypi.org/project/types-aiobotocore-networkmanager/).

- [Literals for aiobotocore NetworkManager module](#literals-for-aiobotocore-networkmanager-module)
  - [AttachmentStateType](#attachmentstatetype)
  - [AttachmentTypeType](#attachmenttypetype)
  - [ChangeActionType](#changeactiontype)
  - [ChangeSetStateType](#changesetstatetype)
  - [ChangeTypeType](#changetypetype)
  - [ConnectPeerAssociationStateType](#connectpeerassociationstatetype)
  - [ConnectPeerStateType](#connectpeerstatetype)
  - [ConnectionStateType](#connectionstatetype)
  - [ConnectionStatusType](#connectionstatustype)
  - [ConnectionTypeType](#connectiontypetype)
  - [CoreNetworkPolicyAliasType](#corenetworkpolicyaliastype)
  - [CoreNetworkStateType](#corenetworkstatetype)
  - [CustomerGatewayAssociationStateType](#customergatewayassociationstatetype)
  - [DescribeGlobalNetworksPaginatorName](#describeglobalnetworkspaginatorname)
  - [DeviceStateType](#devicestatetype)
  - [GetConnectPeerAssociationsPaginatorName](#getconnectpeerassociationspaginatorname)
  - [GetConnectionsPaginatorName](#getconnectionspaginatorname)
  - [GetCoreNetworkChangeSetPaginatorName](#getcorenetworkchangesetpaginatorname)
  - [GetCustomerGatewayAssociationsPaginatorName](#getcustomergatewayassociationspaginatorname)
  - [GetDevicesPaginatorName](#getdevicespaginatorname)
  - [GetLinkAssociationsPaginatorName](#getlinkassociationspaginatorname)
  - [GetLinksPaginatorName](#getlinkspaginatorname)
  - [GetNetworkResourceCountsPaginatorName](#getnetworkresourcecountspaginatorname)
  - [GetNetworkResourceRelationshipsPaginatorName](#getnetworkresourcerelationshipspaginatorname)
  - [GetNetworkResourcesPaginatorName](#getnetworkresourcespaginatorname)
  - [GetNetworkTelemetryPaginatorName](#getnetworktelemetrypaginatorname)
  - [GetSitesPaginatorName](#getsitespaginatorname)
  - [GetTransitGatewayConnectPeerAssociationsPaginatorName](#gettransitgatewayconnectpeerassociationspaginatorname)
  - [GetTransitGatewayRegistrationsPaginatorName](#gettransitgatewayregistrationspaginatorname)
  - [GlobalNetworkStateType](#globalnetworkstatetype)
  - [LinkAssociationStateType](#linkassociationstatetype)
  - [LinkStateType](#linkstatetype)
  - [ListAttachmentsPaginatorName](#listattachmentspaginatorname)
  - [ListConnectPeersPaginatorName](#listconnectpeerspaginatorname)
  - [ListCoreNetworkPolicyVersionsPaginatorName](#listcorenetworkpolicyversionspaginatorname)
  - [ListCoreNetworksPaginatorName](#listcorenetworkspaginatorname)
  - [RouteAnalysisCompletionReasonCodeType](#routeanalysiscompletionreasoncodetype)
  - [RouteAnalysisCompletionResultCodeType](#routeanalysiscompletionresultcodetype)
  - [RouteAnalysisStatusType](#routeanalysisstatustype)
  - [RouteStateType](#routestatetype)
  - [RouteTableTypeType](#routetabletypetype)
  - [RouteTypeType](#routetypetype)
  - [SiteStateType](#sitestatetype)
  - [TransitGatewayConnectPeerAssociationStateType](#transitgatewayconnectpeerassociationstatetype)
  - [TransitGatewayRegistrationStateType](#transitgatewayregistrationstatetype)
  - [TunnelProtocolType](#tunnelprotocoltype)
  - [ServiceName](#servicename)
  - [PaginatorName](#paginatorname)

<a id="attachmentstatetype"></a>

## AttachmentStateType

```python
from types_aiobotocore_networkmanager.literals import AttachmentStateType
```

Values:

- `AVAILABLE`
- `CREATING`
- `DELETING`
- `FAILED`
- `PENDING_ATTACHMENT_ACCEPTANCE`
- `PENDING_NETWORK_UPDATE`
- `PENDING_TAG_ACCEPTANCE`
- `REJECTED`
- `UPDATING`

<a id="attachmenttypetype"></a>

## AttachmentTypeType

```python
from types_aiobotocore_networkmanager.literals import AttachmentTypeType
```

Values:

- `CONNECT`
- `SITE_TO_SITE_VPN`
- `VPC`

<a id="changeactiontype"></a>

## ChangeActionType

```python
from types_aiobotocore_networkmanager.literals import ChangeActionType
```

Values:

- `ADD`
- `MODIFY`
- `REMOVE`

<a id="changesetstatetype"></a>

## ChangeSetStateType

```python
from types_aiobotocore_networkmanager.literals import ChangeSetStateType
```

Values:

- `EXECUTING`
- `EXECUTION_SUCCEEDED`
- `FAILED_GENERATION`
- `OUT_OF_DATE`
- `PENDING_GENERATION`
- `READY_TO_EXECUTE`

<a id="changetypetype"></a>

## ChangeTypeType

```python
from types_aiobotocore_networkmanager.literals import ChangeTypeType
```

Values:

- `ATTACHMENT_MAPPING`
- `ATTACHMENT_ROUTE_PROPAGATION`
- `ATTACHMENT_ROUTE_STATIC`
- `CORE_NETWORK_EDGE`
- `CORE_NETWORK_SEGMENT`

<a id="connectpeerassociationstatetype"></a>

## ConnectPeerAssociationStateType

```python
from types_aiobotocore_networkmanager.literals import ConnectPeerAssociationStateType
```

Values:

- `AVAILABLE`
- `DELETED`
- `DELETING`
- `PENDING`

<a id="connectpeerstatetype"></a>

## ConnectPeerStateType

```python
from types_aiobotocore_networkmanager.literals import ConnectPeerStateType
```

Values:

- `AVAILABLE`
- `CREATING`
- `DELETING`
- `FAILED`

<a id="connectionstatetype"></a>

## ConnectionStateType

```python
from types_aiobotocore_networkmanager.literals import ConnectionStateType
```

Values:

- `AVAILABLE`
- `DELETING`
- `PENDING`
- `UPDATING`

<a id="connectionstatustype"></a>

## ConnectionStatusType

```python
from types_aiobotocore_networkmanager.literals import ConnectionStatusType
```

Values:

- `DOWN`
- `UP`

<a id="connectiontypetype"></a>

## ConnectionTypeType

```python
from types_aiobotocore_networkmanager.literals import ConnectionTypeType
```

Values:

- `BGP`
- `IPSEC`

<a id="corenetworkpolicyaliastype"></a>

## CoreNetworkPolicyAliasType

```python
from types_aiobotocore_networkmanager.literals import CoreNetworkPolicyAliasType
```

Values:

- `LATEST`
- `LIVE`

<a id="corenetworkstatetype"></a>

## CoreNetworkStateType

```python
from types_aiobotocore_networkmanager.literals import CoreNetworkStateType
```

Values:

- `AVAILABLE`
- `CREATING`
- `DELETING`
- `UPDATING`

<a id="customergatewayassociationstatetype"></a>

## CustomerGatewayAssociationStateType

```python
from types_aiobotocore_networkmanager.literals import CustomerGatewayAssociationStateType
```

Values:

- `AVAILABLE`
- `DELETED`
- `DELETING`
- `PENDING`

<a id="describeglobalnetworkspaginatorname"></a>

## DescribeGlobalNetworksPaginatorName

```python
from types_aiobotocore_networkmanager.literals import DescribeGlobalNetworksPaginatorName
```

Values:

- `describe_global_networks`

<a id="devicestatetype"></a>

## DeviceStateType

```python
from types_aiobotocore_networkmanager.literals import DeviceStateType
```

Values:

- `AVAILABLE`
- `DELETING`
- `PENDING`
- `UPDATING`

<a id="getconnectpeerassociationspaginatorname"></a>

## GetConnectPeerAssociationsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetConnectPeerAssociationsPaginatorName
```

Values:

- `get_connect_peer_associations`

<a id="getconnectionspaginatorname"></a>

## GetConnectionsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetConnectionsPaginatorName
```

Values:

- `get_connections`

<a id="getcorenetworkchangesetpaginatorname"></a>

## GetCoreNetworkChangeSetPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetCoreNetworkChangeSetPaginatorName
```

Values:

- `get_core_network_change_set`

<a id="getcustomergatewayassociationspaginatorname"></a>

## GetCustomerGatewayAssociationsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetCustomerGatewayAssociationsPaginatorName
```

Values:

- `get_customer_gateway_associations`

<a id="getdevicespaginatorname"></a>

## GetDevicesPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetDevicesPaginatorName
```

Values:

- `get_devices`

<a id="getlinkassociationspaginatorname"></a>

## GetLinkAssociationsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetLinkAssociationsPaginatorName
```

Values:

- `get_link_associations`

<a id="getlinkspaginatorname"></a>

## GetLinksPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetLinksPaginatorName
```

Values:

- `get_links`

<a id="getnetworkresourcecountspaginatorname"></a>

## GetNetworkResourceCountsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetNetworkResourceCountsPaginatorName
```

Values:

- `get_network_resource_counts`

<a id="getnetworkresourcerelationshipspaginatorname"></a>

## GetNetworkResourceRelationshipsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetNetworkResourceRelationshipsPaginatorName
```

Values:

- `get_network_resource_relationships`

<a id="getnetworkresourcespaginatorname"></a>

## GetNetworkResourcesPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetNetworkResourcesPaginatorName
```

Values:

- `get_network_resources`

<a id="getnetworktelemetrypaginatorname"></a>

## GetNetworkTelemetryPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetNetworkTelemetryPaginatorName
```

Values:

- `get_network_telemetry`

<a id="getsitespaginatorname"></a>

## GetSitesPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetSitesPaginatorName
```

Values:

- `get_sites`

<a id="gettransitgatewayconnectpeerassociationspaginatorname"></a>

## GetTransitGatewayConnectPeerAssociationsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetTransitGatewayConnectPeerAssociationsPaginatorName
```

Values:

- `get_transit_gateway_connect_peer_associations`

<a id="gettransitgatewayregistrationspaginatorname"></a>

## GetTransitGatewayRegistrationsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import GetTransitGatewayRegistrationsPaginatorName
```

Values:

- `get_transit_gateway_registrations`

<a id="globalnetworkstatetype"></a>

## GlobalNetworkStateType

```python
from types_aiobotocore_networkmanager.literals import GlobalNetworkStateType
```

Values:

- `AVAILABLE`
- `DELETING`
- `PENDING`
- `UPDATING`

<a id="linkassociationstatetype"></a>

## LinkAssociationStateType

```python
from types_aiobotocore_networkmanager.literals import LinkAssociationStateType
```

Values:

- `AVAILABLE`
- `DELETED`
- `DELETING`
- `PENDING`

<a id="linkstatetype"></a>

## LinkStateType

```python
from types_aiobotocore_networkmanager.literals import LinkStateType
```

Values:

- `AVAILABLE`
- `DELETING`
- `PENDING`
- `UPDATING`

<a id="listattachmentspaginatorname"></a>

## ListAttachmentsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import ListAttachmentsPaginatorName
```

Values:

- `list_attachments`

<a id="listconnectpeerspaginatorname"></a>

## ListConnectPeersPaginatorName

```python
from types_aiobotocore_networkmanager.literals import ListConnectPeersPaginatorName
```

Values:

- `list_connect_peers`

<a id="listcorenetworkpolicyversionspaginatorname"></a>

## ListCoreNetworkPolicyVersionsPaginatorName

```python
from types_aiobotocore_networkmanager.literals import ListCoreNetworkPolicyVersionsPaginatorName
```

Values:

- `list_core_network_policy_versions`

<a id="listcorenetworkspaginatorname"></a>

## ListCoreNetworksPaginatorName

```python
from types_aiobotocore_networkmanager.literals import ListCoreNetworksPaginatorName
```

Values:

- `list_core_networks`

<a id="routeanalysiscompletionreasoncodetype"></a>

## RouteAnalysisCompletionReasonCodeType

```python
from types_aiobotocore_networkmanager.literals import RouteAnalysisCompletionReasonCodeType
```

Values:

- `BLACKHOLE_ROUTE_FOR_DESTINATION_FOUND`
- `CYCLIC_PATH_DETECTED`
- `INACTIVE_ROUTE_FOR_DESTINATION_FOUND`
- `MAX_HOPS_EXCEEDED`
- `NO_DESTINATION_ARN_PROVIDED`
- `POSSIBLE_MIDDLEBOX`
- `ROUTE_NOT_FOUND`
- `TRANSIT_GATEWAY_ATTACHMENT_ATTACH_ARN_NO_MATCH`
- `TRANSIT_GATEWAY_ATTACHMENT_NOT_FOUND`
- `TRANSIT_GATEWAY_ATTACHMENT_NOT_IN_TRANSIT_GATEWAY`
- `TRANSIT_GATEWAY_ATTACHMENT_STABLE_ROUTE_TABLE_NOT_FOUND`

<a id="routeanalysiscompletionresultcodetype"></a>

## RouteAnalysisCompletionResultCodeType

```python
from types_aiobotocore_networkmanager.literals import RouteAnalysisCompletionResultCodeType
```

Values:

- `CONNECTED`
- `NOT_CONNECTED`

<a id="routeanalysisstatustype"></a>

## RouteAnalysisStatusType

```python
from types_aiobotocore_networkmanager.literals import RouteAnalysisStatusType
```

Values:

- `COMPLETED`
- `FAILED`
- `RUNNING`

<a id="routestatetype"></a>

## RouteStateType

```python
from types_aiobotocore_networkmanager.literals import RouteStateType
```

Values:

- `ACTIVE`
- `BLACKHOLE`

<a id="routetabletypetype"></a>

## RouteTableTypeType

```python
from types_aiobotocore_networkmanager.literals import RouteTableTypeType
```

Values:

- `CORE_NETWORK_SEGMENT`
- `TRANSIT_GATEWAY_ROUTE_TABLE`

<a id="routetypetype"></a>

## RouteTypeType

```python
from types_aiobotocore_networkmanager.literals import RouteTypeType
```

Values:

- `PROPAGATED`
- `STATIC`

<a id="sitestatetype"></a>

## SiteStateType

```python
from types_aiobotocore_networkmanager.literals import SiteStateType
```

Values:

- `AVAILABLE`
- `DELETING`
- `PENDING`
- `UPDATING`

<a id="transitgatewayconnectpeerassociationstatetype"></a>

## TransitGatewayConnectPeerAssociationStateType

```python
from types_aiobotocore_networkmanager.literals import TransitGatewayConnectPeerAssociationStateType
```

Values:

- `AVAILABLE`
- `DELETED`
- `DELETING`
- `PENDING`

<a id="transitgatewayregistrationstatetype"></a>

## TransitGatewayRegistrationStateType

```python
from types_aiobotocore_networkmanager.literals import TransitGatewayRegistrationStateType
```

Values:

- `AVAILABLE`
- `DELETED`
- `DELETING`
- `FAILED`
- `PENDING`

<a id="tunnelprotocoltype"></a>

## TunnelProtocolType

```python
from types_aiobotocore_networkmanager.literals import TunnelProtocolType
```

Values:

- `GRE`

<a id="servicename"></a>

## ServiceName

```python
from types_aiobotocore_networkmanager.literals import ServiceName
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
from types_aiobotocore_networkmanager.literals import PaginatorName
```

Values:

- `describe_global_networks`
- `get_connect_peer_associations`
- `get_connections`
- `get_core_network_change_set`
- `get_customer_gateway_associations`
- `get_devices`
- `get_link_associations`
- `get_links`
- `get_network_resource_counts`
- `get_network_resource_relationships`
- `get_network_resources`
- `get_network_telemetry`
- `get_sites`
- `get_transit_gateway_connect_peer_associations`
- `get_transit_gateway_registrations`
- `list_attachments`
- `list_connect_peers`
- `list_core_network_policy_versions`
- `list_core_networks`
