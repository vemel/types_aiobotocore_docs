<a id="typed-dictionaries-for-aiobotocore-pinpointemail-module"></a>

# Typed dictionaries for aiobotocore PinpointEmail module

> [Index](../README.md) > [PinpointEmail](./README.md) > Typed dictionaries

Auto-generated documentation for
[PinpointEmail](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
type annotations stubs module
[types-aiobotocore-pinpoint-email](https://pypi.org/project/types-aiobotocore-pinpoint-email/).

- [Typed dictionaries for aiobotocore PinpointEmail module](#typed-dictionaries-for-aiobotocore-pinpointemail-module)
  - [BlacklistEntryTypeDef](#blacklistentrytypedef)
  - [BodyTypeDef](#bodytypedef)
  - [CloudWatchDestinationTypeDef](#cloudwatchdestinationtypedef)
  - [CloudWatchDimensionConfigurationTypeDef](#cloudwatchdimensionconfigurationtypedef)
  - [ContentTypeDef](#contenttypedef)
  - [CreateConfigurationSetEventDestinationRequestRequestTypeDef](#createconfigurationseteventdestinationrequestrequesttypedef)
  - [CreateConfigurationSetRequestRequestTypeDef](#createconfigurationsetrequestrequesttypedef)
  - [CreateDedicatedIpPoolRequestRequestTypeDef](#creatededicatedippoolrequestrequesttypedef)
  - [CreateDeliverabilityTestReportRequestRequestTypeDef](#createdeliverabilitytestreportrequestrequesttypedef)
  - [CreateDeliverabilityTestReportResponseTypeDef](#createdeliverabilitytestreportresponsetypedef)
  - [CreateEmailIdentityRequestRequestTypeDef](#createemailidentityrequestrequesttypedef)
  - [CreateEmailIdentityResponseTypeDef](#createemailidentityresponsetypedef)
  - [DailyVolumeTypeDef](#dailyvolumetypedef)
  - [DedicatedIpTypeDef](#dedicatediptypedef)
  - [DeleteConfigurationSetEventDestinationRequestRequestTypeDef](#deleteconfigurationseteventdestinationrequestrequesttypedef)
  - [DeleteConfigurationSetRequestRequestTypeDef](#deleteconfigurationsetrequestrequesttypedef)
  - [DeleteDedicatedIpPoolRequestRequestTypeDef](#deletededicatedippoolrequestrequesttypedef)
  - [DeleteEmailIdentityRequestRequestTypeDef](#deleteemailidentityrequestrequesttypedef)
  - [DeliverabilityTestReportTypeDef](#deliverabilitytestreporttypedef)
  - [DeliveryOptionsTypeDef](#deliveryoptionstypedef)
  - [DestinationTypeDef](#destinationtypedef)
  - [DkimAttributesTypeDef](#dkimattributestypedef)
  - [DomainDeliverabilityCampaignTypeDef](#domaindeliverabilitycampaigntypedef)
  - [DomainDeliverabilityTrackingOptionTypeDef](#domaindeliverabilitytrackingoptiontypedef)
  - [DomainIspPlacementTypeDef](#domainispplacementtypedef)
  - [EmailContentTypeDef](#emailcontenttypedef)
  - [EventDestinationDefinitionTypeDef](#eventdestinationdefinitiontypedef)
  - [EventDestinationTypeDef](#eventdestinationtypedef)
  - [GetAccountResponseTypeDef](#getaccountresponsetypedef)
  - [GetBlacklistReportsRequestRequestTypeDef](#getblacklistreportsrequestrequesttypedef)
  - [GetBlacklistReportsResponseTypeDef](#getblacklistreportsresponsetypedef)
  - [GetConfigurationSetEventDestinationsRequestRequestTypeDef](#getconfigurationseteventdestinationsrequestrequesttypedef)
  - [GetConfigurationSetEventDestinationsResponseTypeDef](#getconfigurationseteventdestinationsresponsetypedef)
  - [GetConfigurationSetRequestRequestTypeDef](#getconfigurationsetrequestrequesttypedef)
  - [GetConfigurationSetResponseTypeDef](#getconfigurationsetresponsetypedef)
  - [GetDedicatedIpRequestRequestTypeDef](#getdedicatediprequestrequesttypedef)
  - [GetDedicatedIpResponseTypeDef](#getdedicatedipresponsetypedef)
  - [GetDedicatedIpsRequestRequestTypeDef](#getdedicatedipsrequestrequesttypedef)
  - [GetDedicatedIpsResponseTypeDef](#getdedicatedipsresponsetypedef)
  - [GetDeliverabilityDashboardOptionsResponseTypeDef](#getdeliverabilitydashboardoptionsresponsetypedef)
  - [GetDeliverabilityTestReportRequestRequestTypeDef](#getdeliverabilitytestreportrequestrequesttypedef)
  - [GetDeliverabilityTestReportResponseTypeDef](#getdeliverabilitytestreportresponsetypedef)
  - [GetDomainDeliverabilityCampaignRequestRequestTypeDef](#getdomaindeliverabilitycampaignrequestrequesttypedef)
  - [GetDomainDeliverabilityCampaignResponseTypeDef](#getdomaindeliverabilitycampaignresponsetypedef)
  - [GetDomainStatisticsReportRequestRequestTypeDef](#getdomainstatisticsreportrequestrequesttypedef)
  - [GetDomainStatisticsReportResponseTypeDef](#getdomainstatisticsreportresponsetypedef)
  - [GetEmailIdentityRequestRequestTypeDef](#getemailidentityrequestrequesttypedef)
  - [GetEmailIdentityResponseTypeDef](#getemailidentityresponsetypedef)
  - [IdentityInfoTypeDef](#identityinfotypedef)
  - [InboxPlacementTrackingOptionTypeDef](#inboxplacementtrackingoptiontypedef)
  - [IspPlacementTypeDef](#ispplacementtypedef)
  - [KinesisFirehoseDestinationTypeDef](#kinesisfirehosedestinationtypedef)
  - [ListConfigurationSetsRequestRequestTypeDef](#listconfigurationsetsrequestrequesttypedef)
  - [ListConfigurationSetsResponseTypeDef](#listconfigurationsetsresponsetypedef)
  - [ListDedicatedIpPoolsRequestRequestTypeDef](#listdedicatedippoolsrequestrequesttypedef)
  - [ListDedicatedIpPoolsResponseTypeDef](#listdedicatedippoolsresponsetypedef)
  - [ListDeliverabilityTestReportsRequestRequestTypeDef](#listdeliverabilitytestreportsrequestrequesttypedef)
  - [ListDeliverabilityTestReportsResponseTypeDef](#listdeliverabilitytestreportsresponsetypedef)
  - [ListDomainDeliverabilityCampaignsRequestRequestTypeDef](#listdomaindeliverabilitycampaignsrequestrequesttypedef)
  - [ListDomainDeliverabilityCampaignsResponseTypeDef](#listdomaindeliverabilitycampaignsresponsetypedef)
  - [ListEmailIdentitiesRequestRequestTypeDef](#listemailidentitiesrequestrequesttypedef)
  - [ListEmailIdentitiesResponseTypeDef](#listemailidentitiesresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MailFromAttributesTypeDef](#mailfromattributestypedef)
  - [MessageTagTypeDef](#messagetagtypedef)
  - [MessageTypeDef](#messagetypedef)
  - [OverallVolumeTypeDef](#overallvolumetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PinpointDestinationTypeDef](#pinpointdestinationtypedef)
  - [PlacementStatisticsTypeDef](#placementstatisticstypedef)
  - [PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef](#putaccountdedicatedipwarmupattributesrequestrequesttypedef)
  - [PutAccountSendingAttributesRequestRequestTypeDef](#putaccountsendingattributesrequestrequesttypedef)
  - [PutConfigurationSetDeliveryOptionsRequestRequestTypeDef](#putconfigurationsetdeliveryoptionsrequestrequesttypedef)
  - [PutConfigurationSetReputationOptionsRequestRequestTypeDef](#putconfigurationsetreputationoptionsrequestrequesttypedef)
  - [PutConfigurationSetSendingOptionsRequestRequestTypeDef](#putconfigurationsetsendingoptionsrequestrequesttypedef)
  - [PutConfigurationSetTrackingOptionsRequestRequestTypeDef](#putconfigurationsettrackingoptionsrequestrequesttypedef)
  - [PutDedicatedIpInPoolRequestRequestTypeDef](#putdedicatedipinpoolrequestrequesttypedef)
  - [PutDedicatedIpWarmupAttributesRequestRequestTypeDef](#putdedicatedipwarmupattributesrequestrequesttypedef)
  - [PutDeliverabilityDashboardOptionRequestRequestTypeDef](#putdeliverabilitydashboardoptionrequestrequesttypedef)
  - [PutEmailIdentityDkimAttributesRequestRequestTypeDef](#putemailidentitydkimattributesrequestrequesttypedef)
  - [PutEmailIdentityFeedbackAttributesRequestRequestTypeDef](#putemailidentityfeedbackattributesrequestrequesttypedef)
  - [PutEmailIdentityMailFromAttributesRequestRequestTypeDef](#putemailidentitymailfromattributesrequestrequesttypedef)
  - [RawMessageTypeDef](#rawmessagetypedef)
  - [ReputationOptionsTypeDef](#reputationoptionstypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SendEmailRequestRequestTypeDef](#sendemailrequestrequesttypedef)
  - [SendEmailResponseTypeDef](#sendemailresponsetypedef)
  - [SendQuotaTypeDef](#sendquotatypedef)
  - [SendingOptionsTypeDef](#sendingoptionstypedef)
  - [SnsDestinationTypeDef](#snsdestinationtypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [TemplateTypeDef](#templatetypedef)
  - [TrackingOptionsTypeDef](#trackingoptionstypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateConfigurationSetEventDestinationRequestRequestTypeDef](#updateconfigurationseteventdestinationrequestrequesttypedef)
  - [VolumeStatisticsTypeDef](#volumestatisticstypedef)

<a id="blacklistentrytypedef"></a>

## BlacklistEntryTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import BlacklistEntryTypeDef
```

Optional fields:

- `RblName`: `str`
- `ListingTime`: `datetime`
- `Description`: `str`

<a id="bodytypedef"></a>

## BodyTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import BodyTypeDef
```

Optional fields:

- `Text`: [ContentTypeDef](./type_defs.md#contenttypedef)
- `Html`: [ContentTypeDef](./type_defs.md#contenttypedef)

<a id="cloudwatchdestinationtypedef"></a>

## CloudWatchDestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CloudWatchDestinationTypeDef
```

Required fields:

- `DimensionConfigurations`:
  `Sequence`\[[CloudWatchDimensionConfigurationTypeDef](./type_defs.md#cloudwatchdimensionconfigurationtypedef)\]

<a id="cloudwatchdimensionconfigurationtypedef"></a>

## CloudWatchDimensionConfigurationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CloudWatchDimensionConfigurationTypeDef
```

Required fields:

- `DimensionName`: `str`
- `DimensionValueSource`:
  [DimensionValueSourceType](./literals.md#dimensionvaluesourcetype)
- `DefaultDimensionValue`: `str`

<a id="contenttypedef"></a>

## ContentTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ContentTypeDef
```

Required fields:

- `Data`: `str`

Optional fields:

- `Charset`: `str`

<a id="createconfigurationseteventdestinationrequestrequesttypedef"></a>

## CreateConfigurationSetEventDestinationRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateConfigurationSetEventDestinationRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`
- `EventDestinationName`: `str`
- `EventDestination`:
  [EventDestinationDefinitionTypeDef](./type_defs.md#eventdestinationdefinitiontypedef)

<a id="createconfigurationsetrequestrequesttypedef"></a>

## CreateConfigurationSetRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateConfigurationSetRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

Optional fields:

- `TrackingOptions`:
  [TrackingOptionsTypeDef](./type_defs.md#trackingoptionstypedef)
- `DeliveryOptions`:
  [DeliveryOptionsTypeDef](./type_defs.md#deliveryoptionstypedef)
- `ReputationOptions`:
  [ReputationOptionsTypeDef](./type_defs.md#reputationoptionstypedef)
- `SendingOptions`:
  [SendingOptionsTypeDef](./type_defs.md#sendingoptionstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="creatededicatedippoolrequestrequesttypedef"></a>

## CreateDedicatedIpPoolRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateDedicatedIpPoolRequestRequestTypeDef
```

Required fields:

- `PoolName`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdeliverabilitytestreportrequestrequesttypedef"></a>

## CreateDeliverabilityTestReportRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateDeliverabilityTestReportRequestRequestTypeDef
```

Required fields:

- `FromEmailAddress`: `str`
- `Content`: [EmailContentTypeDef](./type_defs.md#emailcontenttypedef)

Optional fields:

- `ReportName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdeliverabilitytestreportresponsetypedef"></a>

## CreateDeliverabilityTestReportResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateDeliverabilityTestReportResponseTypeDef
```

Required fields:

- `ReportId`: `str`
- `DeliverabilityTestStatus`:
  [DeliverabilityTestStatusType](./literals.md#deliverabilityteststatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createemailidentityrequestrequesttypedef"></a>

## CreateEmailIdentityRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateEmailIdentityRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createemailidentityresponsetypedef"></a>

## CreateEmailIdentityResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import CreateEmailIdentityResponseTypeDef
```

Required fields:

- `IdentityType`: [IdentityTypeType](./literals.md#identitytypetype)
- `VerifiedForSendingStatus`: `bool`
- `DkimAttributes`:
  [DkimAttributesTypeDef](./type_defs.md#dkimattributestypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dailyvolumetypedef"></a>

## DailyVolumeTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DailyVolumeTypeDef
```

Optional fields:

- `StartDate`: `datetime`
- `VolumeStatistics`:
  [VolumeStatisticsTypeDef](./type_defs.md#volumestatisticstypedef)
- `DomainIspPlacements`:
  `List`\[[DomainIspPlacementTypeDef](./type_defs.md#domainispplacementtypedef)\]

<a id="dedicatediptypedef"></a>

## DedicatedIpTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DedicatedIpTypeDef
```

Required fields:

- `Ip`: `str`
- `WarmupStatus`: [WarmupStatusType](./literals.md#warmupstatustype)
- `WarmupPercentage`: `int`

Optional fields:

- `PoolName`: `str`

<a id="deleteconfigurationseteventdestinationrequestrequesttypedef"></a>

## DeleteConfigurationSetEventDestinationRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeleteConfigurationSetEventDestinationRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`
- `EventDestinationName`: `str`

<a id="deleteconfigurationsetrequestrequesttypedef"></a>

## DeleteConfigurationSetRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeleteConfigurationSetRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

<a id="deletededicatedippoolrequestrequesttypedef"></a>

## DeleteDedicatedIpPoolRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeleteDedicatedIpPoolRequestRequestTypeDef
```

Required fields:

- `PoolName`: `str`

<a id="deleteemailidentityrequestrequesttypedef"></a>

## DeleteEmailIdentityRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeleteEmailIdentityRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

<a id="deliverabilitytestreporttypedef"></a>

## DeliverabilityTestReportTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeliverabilityTestReportTypeDef
```

Optional fields:

- `ReportId`: `str`
- `ReportName`: `str`
- `Subject`: `str`
- `FromEmailAddress`: `str`
- `CreateDate`: `datetime`
- `DeliverabilityTestStatus`:
  [DeliverabilityTestStatusType](./literals.md#deliverabilityteststatustype)

<a id="deliveryoptionstypedef"></a>

## DeliveryOptionsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DeliveryOptionsTypeDef
```

Optional fields:

- `TlsPolicy`: [TlsPolicyType](./literals.md#tlspolicytype)
- `SendingPoolName`: `str`

<a id="destinationtypedef"></a>

## DestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DestinationTypeDef
```

Optional fields:

- `ToAddresses`: `Sequence`\[`str`\]
- `CcAddresses`: `Sequence`\[`str`\]
- `BccAddresses`: `Sequence`\[`str`\]

<a id="dkimattributestypedef"></a>

## DkimAttributesTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DkimAttributesTypeDef
```

Optional fields:

- `SigningEnabled`: `bool`
- `Status`: [DkimStatusType](./literals.md#dkimstatustype)
- `Tokens`: `List`\[`str`\]

<a id="domaindeliverabilitycampaigntypedef"></a>

## DomainDeliverabilityCampaignTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DomainDeliverabilityCampaignTypeDef
```

Optional fields:

- `CampaignId`: `str`
- `ImageUrl`: `str`
- `Subject`: `str`
- `FromAddress`: `str`
- `SendingIps`: `List`\[`str`\]
- `FirstSeenDateTime`: `datetime`
- `LastSeenDateTime`: `datetime`
- `InboxCount`: `int`
- `SpamCount`: `int`
- `ReadRate`: `float`
- `DeleteRate`: `float`
- `ReadDeleteRate`: `float`
- `ProjectedVolume`: `int`
- `Esps`: `List`\[`str`\]

<a id="domaindeliverabilitytrackingoptiontypedef"></a>

## DomainDeliverabilityTrackingOptionTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DomainDeliverabilityTrackingOptionTypeDef
```

Optional fields:

- `Domain`: `str`
- `SubscriptionStartDate`: `datetime`
- `InboxPlacementTrackingOption`:
  [InboxPlacementTrackingOptionTypeDef](./type_defs.md#inboxplacementtrackingoptiontypedef)

<a id="domainispplacementtypedef"></a>

## DomainIspPlacementTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import DomainIspPlacementTypeDef
```

Optional fields:

- `IspName`: `str`
- `InboxRawCount`: `int`
- `SpamRawCount`: `int`
- `InboxPercentage`: `float`
- `SpamPercentage`: `float`

<a id="emailcontenttypedef"></a>

## EmailContentTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import EmailContentTypeDef
```

Optional fields:

- `Simple`: [MessageTypeDef](./type_defs.md#messagetypedef)
- `Raw`: [RawMessageTypeDef](./type_defs.md#rawmessagetypedef)
- `Template`: [TemplateTypeDef](./type_defs.md#templatetypedef)

<a id="eventdestinationdefinitiontypedef"></a>

## EventDestinationDefinitionTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import EventDestinationDefinitionTypeDef
```

Optional fields:

- `Enabled`: `bool`
- `MatchingEventTypes`:
  `Sequence`\[[EventTypeType](./literals.md#eventtypetype)\]
- `KinesisFirehoseDestination`:
  [KinesisFirehoseDestinationTypeDef](./type_defs.md#kinesisfirehosedestinationtypedef)
- `CloudWatchDestination`:
  [CloudWatchDestinationTypeDef](./type_defs.md#cloudwatchdestinationtypedef)
- `SnsDestination`:
  [SnsDestinationTypeDef](./type_defs.md#snsdestinationtypedef)
- `PinpointDestination`:
  [PinpointDestinationTypeDef](./type_defs.md#pinpointdestinationtypedef)

<a id="eventdestinationtypedef"></a>

## EventDestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import EventDestinationTypeDef
```

Required fields:

- `Name`: `str`
- `MatchingEventTypes`: `List`\[[EventTypeType](./literals.md#eventtypetype)\]

Optional fields:

- `Enabled`: `bool`
- `KinesisFirehoseDestination`:
  [KinesisFirehoseDestinationTypeDef](./type_defs.md#kinesisfirehosedestinationtypedef)
- `CloudWatchDestination`:
  [CloudWatchDestinationTypeDef](./type_defs.md#cloudwatchdestinationtypedef)
- `SnsDestination`:
  [SnsDestinationTypeDef](./type_defs.md#snsdestinationtypedef)
- `PinpointDestination`:
  [PinpointDestinationTypeDef](./type_defs.md#pinpointdestinationtypedef)

<a id="getaccountresponsetypedef"></a>

## GetAccountResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetAccountResponseTypeDef
```

Required fields:

- `SendQuota`: [SendQuotaTypeDef](./type_defs.md#sendquotatypedef)
- `SendingEnabled`: `bool`
- `DedicatedIpAutoWarmupEnabled`: `bool`
- `EnforcementStatus`: `str`
- `ProductionAccessEnabled`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getblacklistreportsrequestrequesttypedef"></a>

## GetBlacklistReportsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetBlacklistReportsRequestRequestTypeDef
```

Required fields:

- `BlacklistItemNames`: `Sequence`\[`str`\]

<a id="getblacklistreportsresponsetypedef"></a>

## GetBlacklistReportsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetBlacklistReportsResponseTypeDef
```

Required fields:

- `BlacklistReport`: `Dict`\[`str`,
  `List`\[[BlacklistEntryTypeDef](./type_defs.md#blacklistentrytypedef)\]\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getconfigurationseteventdestinationsrequestrequesttypedef"></a>

## GetConfigurationSetEventDestinationsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetConfigurationSetEventDestinationsRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

<a id="getconfigurationseteventdestinationsresponsetypedef"></a>

## GetConfigurationSetEventDestinationsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetConfigurationSetEventDestinationsResponseTypeDef
```

Required fields:

- `EventDestinations`:
  `List`\[[EventDestinationTypeDef](./type_defs.md#eventdestinationtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getconfigurationsetrequestrequesttypedef"></a>

## GetConfigurationSetRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetConfigurationSetRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

<a id="getconfigurationsetresponsetypedef"></a>

## GetConfigurationSetResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetConfigurationSetResponseTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`
- `TrackingOptions`:
  [TrackingOptionsTypeDef](./type_defs.md#trackingoptionstypedef)
- `DeliveryOptions`:
  [DeliveryOptionsTypeDef](./type_defs.md#deliveryoptionstypedef)
- `ReputationOptions`:
  [ReputationOptionsTypeDef](./type_defs.md#reputationoptionstypedef)
- `SendingOptions`:
  [SendingOptionsTypeDef](./type_defs.md#sendingoptionstypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdedicatediprequestrequesttypedef"></a>

## GetDedicatedIpRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDedicatedIpRequestRequestTypeDef
```

Required fields:

- `Ip`: `str`

<a id="getdedicatedipresponsetypedef"></a>

## GetDedicatedIpResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDedicatedIpResponseTypeDef
```

Required fields:

- `DedicatedIp`: [DedicatedIpTypeDef](./type_defs.md#dedicatediptypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdedicatedipsrequestrequesttypedef"></a>

## GetDedicatedIpsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDedicatedIpsRequestRequestTypeDef
```

Optional fields:

- `PoolName`: `str`
- `NextToken`: `str`
- `PageSize`: `int`

<a id="getdedicatedipsresponsetypedef"></a>

## GetDedicatedIpsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDedicatedIpsResponseTypeDef
```

Required fields:

- `DedicatedIps`:
  `List`\[[DedicatedIpTypeDef](./type_defs.md#dedicatediptypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdeliverabilitydashboardoptionsresponsetypedef"></a>

## GetDeliverabilityDashboardOptionsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDeliverabilityDashboardOptionsResponseTypeDef
```

Required fields:

- `DashboardEnabled`: `bool`
- `SubscriptionExpiryDate`: `datetime`
- `AccountStatus`:
  [DeliverabilityDashboardAccountStatusType](./literals.md#deliverabilitydashboardaccountstatustype)
- `ActiveSubscribedDomains`:
  `List`\[[DomainDeliverabilityTrackingOptionTypeDef](./type_defs.md#domaindeliverabilitytrackingoptiontypedef)\]
- `PendingExpirationSubscribedDomains`:
  `List`\[[DomainDeliverabilityTrackingOptionTypeDef](./type_defs.md#domaindeliverabilitytrackingoptiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdeliverabilitytestreportrequestrequesttypedef"></a>

## GetDeliverabilityTestReportRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDeliverabilityTestReportRequestRequestTypeDef
```

Required fields:

- `ReportId`: `str`

<a id="getdeliverabilitytestreportresponsetypedef"></a>

## GetDeliverabilityTestReportResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDeliverabilityTestReportResponseTypeDef
```

Required fields:

- `DeliverabilityTestReport`:
  [DeliverabilityTestReportTypeDef](./type_defs.md#deliverabilitytestreporttypedef)
- `OverallPlacement`:
  [PlacementStatisticsTypeDef](./type_defs.md#placementstatisticstypedef)
- `IspPlacements`:
  `List`\[[IspPlacementTypeDef](./type_defs.md#ispplacementtypedef)\]
- `Message`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdomaindeliverabilitycampaignrequestrequesttypedef"></a>

## GetDomainDeliverabilityCampaignRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDomainDeliverabilityCampaignRequestRequestTypeDef
```

Required fields:

- `CampaignId`: `str`

<a id="getdomaindeliverabilitycampaignresponsetypedef"></a>

## GetDomainDeliverabilityCampaignResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDomainDeliverabilityCampaignResponseTypeDef
```

Required fields:

- `DomainDeliverabilityCampaign`:
  [DomainDeliverabilityCampaignTypeDef](./type_defs.md#domaindeliverabilitycampaigntypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getdomainstatisticsreportrequestrequesttypedef"></a>

## GetDomainStatisticsReportRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDomainStatisticsReportRequestRequestTypeDef
```

Required fields:

- `Domain`: `str`
- `StartDate`: `Union`\[`datetime`, `str`\]
- `EndDate`: `Union`\[`datetime`, `str`\]

<a id="getdomainstatisticsreportresponsetypedef"></a>

## GetDomainStatisticsReportResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetDomainStatisticsReportResponseTypeDef
```

Required fields:

- `OverallVolume`: [OverallVolumeTypeDef](./type_defs.md#overallvolumetypedef)
- `DailyVolumes`:
  `List`\[[DailyVolumeTypeDef](./type_defs.md#dailyvolumetypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getemailidentityrequestrequesttypedef"></a>

## GetEmailIdentityRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetEmailIdentityRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

<a id="getemailidentityresponsetypedef"></a>

## GetEmailIdentityResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import GetEmailIdentityResponseTypeDef
```

Required fields:

- `IdentityType`: [IdentityTypeType](./literals.md#identitytypetype)
- `FeedbackForwardingStatus`: `bool`
- `VerifiedForSendingStatus`: `bool`
- `DkimAttributes`:
  [DkimAttributesTypeDef](./type_defs.md#dkimattributestypedef)
- `MailFromAttributes`:
  [MailFromAttributesTypeDef](./type_defs.md#mailfromattributestypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="identityinfotypedef"></a>

## IdentityInfoTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import IdentityInfoTypeDef
```

Optional fields:

- `IdentityType`: [IdentityTypeType](./literals.md#identitytypetype)
- `IdentityName`: `str`
- `SendingEnabled`: `bool`

<a id="inboxplacementtrackingoptiontypedef"></a>

## InboxPlacementTrackingOptionTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import InboxPlacementTrackingOptionTypeDef
```

Optional fields:

- `Global`: `bool`
- `TrackedIsps`: `List`\[`str`\]

<a id="ispplacementtypedef"></a>

## IspPlacementTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import IspPlacementTypeDef
```

Optional fields:

- `IspName`: `str`
- `PlacementStatistics`:
  [PlacementStatisticsTypeDef](./type_defs.md#placementstatisticstypedef)

<a id="kinesisfirehosedestinationtypedef"></a>

## KinesisFirehoseDestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import KinesisFirehoseDestinationTypeDef
```

Required fields:

- `IamRoleArn`: `str`
- `DeliveryStreamArn`: `str`

<a id="listconfigurationsetsrequestrequesttypedef"></a>

## ListConfigurationSetsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListConfigurationSetsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="listconfigurationsetsresponsetypedef"></a>

## ListConfigurationSetsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListConfigurationSetsResponseTypeDef
```

Required fields:

- `ConfigurationSets`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdedicatedippoolsrequestrequesttypedef"></a>

## ListDedicatedIpPoolsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDedicatedIpPoolsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="listdedicatedippoolsresponsetypedef"></a>

## ListDedicatedIpPoolsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDedicatedIpPoolsResponseTypeDef
```

Required fields:

- `DedicatedIpPools`: `List`\[`str`\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdeliverabilitytestreportsrequestrequesttypedef"></a>

## ListDeliverabilityTestReportsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDeliverabilityTestReportsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="listdeliverabilitytestreportsresponsetypedef"></a>

## ListDeliverabilityTestReportsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDeliverabilityTestReportsResponseTypeDef
```

Required fields:

- `DeliverabilityTestReports`:
  `List`\[[DeliverabilityTestReportTypeDef](./type_defs.md#deliverabilitytestreporttypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdomaindeliverabilitycampaignsrequestrequesttypedef"></a>

## ListDomainDeliverabilityCampaignsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDomainDeliverabilityCampaignsRequestRequestTypeDef
```

Required fields:

- `StartDate`: `Union`\[`datetime`, `str`\]
- `EndDate`: `Union`\[`datetime`, `str`\]
- `SubscribedDomain`: `str`

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="listdomaindeliverabilitycampaignsresponsetypedef"></a>

## ListDomainDeliverabilityCampaignsResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListDomainDeliverabilityCampaignsResponseTypeDef
```

Required fields:

- `DomainDeliverabilityCampaigns`:
  `List`\[[DomainDeliverabilityCampaignTypeDef](./type_defs.md#domaindeliverabilitycampaigntypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listemailidentitiesrequestrequesttypedef"></a>

## ListEmailIdentitiesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListEmailIdentitiesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `PageSize`: `int`

<a id="listemailidentitiesresponsetypedef"></a>

## ListEmailIdentitiesResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListEmailIdentitiesResponseTypeDef
```

Required fields:

- `EmailIdentities`:
  `List`\[[IdentityInfoTypeDef](./type_defs.md#identityinfotypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mailfromattributestypedef"></a>

## MailFromAttributesTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import MailFromAttributesTypeDef
```

Required fields:

- `MailFromDomain`: `str`
- `MailFromDomainStatus`:
  [MailFromDomainStatusType](./literals.md#mailfromdomainstatustype)
- `BehaviorOnMxFailure`:
  [BehaviorOnMxFailureType](./literals.md#behavioronmxfailuretype)

<a id="messagetagtypedef"></a>

## MessageTagTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import MessageTagTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="messagetypedef"></a>

## MessageTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import MessageTypeDef
```

Required fields:

- `Subject`: [ContentTypeDef](./type_defs.md#contenttypedef)
- `Body`: [BodyTypeDef](./type_defs.md#bodytypedef)

<a id="overallvolumetypedef"></a>

## OverallVolumeTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import OverallVolumeTypeDef
```

Optional fields:

- `VolumeStatistics`:
  [VolumeStatisticsTypeDef](./type_defs.md#volumestatisticstypedef)
- `ReadRatePercent`: `float`
- `DomainIspPlacements`:
  `List`\[[DomainIspPlacementTypeDef](./type_defs.md#domainispplacementtypedef)\]

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="pinpointdestinationtypedef"></a>

## PinpointDestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PinpointDestinationTypeDef
```

Optional fields:

- `ApplicationArn`: `str`

<a id="placementstatisticstypedef"></a>

## PlacementStatisticsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PlacementStatisticsTypeDef
```

Optional fields:

- `InboxPercentage`: `float`
- `SpamPercentage`: `float`
- `MissingPercentage`: `float`
- `SpfPercentage`: `float`
- `DkimPercentage`: `float`

<a id="putaccountdedicatedipwarmupattributesrequestrequesttypedef"></a>

## PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef
```

Optional fields:

- `AutoWarmupEnabled`: `bool`

<a id="putaccountsendingattributesrequestrequesttypedef"></a>

## PutAccountSendingAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutAccountSendingAttributesRequestRequestTypeDef
```

Optional fields:

- `SendingEnabled`: `bool`

<a id="putconfigurationsetdeliveryoptionsrequestrequesttypedef"></a>

## PutConfigurationSetDeliveryOptionsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutConfigurationSetDeliveryOptionsRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

Optional fields:

- `TlsPolicy`: [TlsPolicyType](./literals.md#tlspolicytype)
- `SendingPoolName`: `str`

<a id="putconfigurationsetreputationoptionsrequestrequesttypedef"></a>

## PutConfigurationSetReputationOptionsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutConfigurationSetReputationOptionsRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

Optional fields:

- `ReputationMetricsEnabled`: `bool`

<a id="putconfigurationsetsendingoptionsrequestrequesttypedef"></a>

## PutConfigurationSetSendingOptionsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutConfigurationSetSendingOptionsRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

Optional fields:

- `SendingEnabled`: `bool`

<a id="putconfigurationsettrackingoptionsrequestrequesttypedef"></a>

## PutConfigurationSetTrackingOptionsRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutConfigurationSetTrackingOptionsRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`

Optional fields:

- `CustomRedirectDomain`: `str`

<a id="putdedicatedipinpoolrequestrequesttypedef"></a>

## PutDedicatedIpInPoolRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutDedicatedIpInPoolRequestRequestTypeDef
```

Required fields:

- `Ip`: `str`
- `DestinationPoolName`: `str`

<a id="putdedicatedipwarmupattributesrequestrequesttypedef"></a>

## PutDedicatedIpWarmupAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutDedicatedIpWarmupAttributesRequestRequestTypeDef
```

Required fields:

- `Ip`: `str`
- `WarmupPercentage`: `int`

<a id="putdeliverabilitydashboardoptionrequestrequesttypedef"></a>

## PutDeliverabilityDashboardOptionRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutDeliverabilityDashboardOptionRequestRequestTypeDef
```

Required fields:

- `DashboardEnabled`: `bool`

Optional fields:

- `SubscribedDomains`:
  `Sequence`\[[DomainDeliverabilityTrackingOptionTypeDef](./type_defs.md#domaindeliverabilitytrackingoptiontypedef)\]

<a id="putemailidentitydkimattributesrequestrequesttypedef"></a>

## PutEmailIdentityDkimAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutEmailIdentityDkimAttributesRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

Optional fields:

- `SigningEnabled`: `bool`

<a id="putemailidentityfeedbackattributesrequestrequesttypedef"></a>

## PutEmailIdentityFeedbackAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutEmailIdentityFeedbackAttributesRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

Optional fields:

- `EmailForwardingEnabled`: `bool`

<a id="putemailidentitymailfromattributesrequestrequesttypedef"></a>

## PutEmailIdentityMailFromAttributesRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import PutEmailIdentityMailFromAttributesRequestRequestTypeDef
```

Required fields:

- `EmailIdentity`: `str`

Optional fields:

- `MailFromDomain`: `str`
- `BehaviorOnMxFailure`:
  [BehaviorOnMxFailureType](./literals.md#behavioronmxfailuretype)

<a id="rawmessagetypedef"></a>

## RawMessageTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import RawMessageTypeDef
```

Required fields:

- `Data`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]

<a id="reputationoptionstypedef"></a>

## ReputationOptionsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ReputationOptionsTypeDef
```

Optional fields:

- `ReputationMetricsEnabled`: `bool`
- `LastFreshStart`: `Union`\[`datetime`, `str`\]

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sendemailrequestrequesttypedef"></a>

## SendEmailRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import SendEmailRequestRequestTypeDef
```

Required fields:

- `Destination`: [DestinationTypeDef](./type_defs.md#destinationtypedef)
- `Content`: [EmailContentTypeDef](./type_defs.md#emailcontenttypedef)

Optional fields:

- `FromEmailAddress`: `str`
- `ReplyToAddresses`: `Sequence`\[`str`\]
- `FeedbackForwardingEmailAddress`: `str`
- `EmailTags`:
  `Sequence`\[[MessageTagTypeDef](./type_defs.md#messagetagtypedef)\]
- `ConfigurationSetName`: `str`

<a id="sendemailresponsetypedef"></a>

## SendEmailResponseTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import SendEmailResponseTypeDef
```

Required fields:

- `MessageId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="sendquotatypedef"></a>

## SendQuotaTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import SendQuotaTypeDef
```

Optional fields:

- `Max24HourSend`: `float`
- `MaxSendRate`: `float`
- `SentLast24Hours`: `float`

<a id="sendingoptionstypedef"></a>

## SendingOptionsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import SendingOptionsTypeDef
```

Optional fields:

- `SendingEnabled`: `bool`

<a id="snsdestinationtypedef"></a>

## SnsDestinationTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import SnsDestinationTypeDef
```

Required fields:

- `TopicArn`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="templatetypedef"></a>

## TemplateTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import TemplateTypeDef
```

Optional fields:

- `TemplateArn`: `str`
- `TemplateData`: `str`

<a id="trackingoptionstypedef"></a>

## TrackingOptionsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import TrackingOptionsTypeDef
```

Required fields:

- `CustomRedirectDomain`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateconfigurationseteventdestinationrequestrequesttypedef"></a>

## UpdateConfigurationSetEventDestinationRequestRequestTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import UpdateConfigurationSetEventDestinationRequestRequestTypeDef
```

Required fields:

- `ConfigurationSetName`: `str`
- `EventDestinationName`: `str`
- `EventDestination`:
  [EventDestinationDefinitionTypeDef](./type_defs.md#eventdestinationdefinitiontypedef)

<a id="volumestatisticstypedef"></a>

## VolumeStatisticsTypeDef

```python
from types_aiobotocore_pinpoint_email.type_defs import VolumeStatisticsTypeDef
```

Optional fields:

- `InboxRawCount`: `int`
- `SpamRawCount`: `int`
- `ProjectedInbox`: `int`
- `ProjectedSpam`: `int`
