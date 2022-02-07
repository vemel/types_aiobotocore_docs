<a id="type-annotations-for-aiobotocore-alexaforbusiness-module"></a>

# Type annotations for aiobotocore AlexaForBusiness module

> [Index](..) > AlexaForBusiness

Auto-generated documentation for
[AlexaForBusiness](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
type annotations stubs module
[types-aiobotocore-alexaforbusiness](https://pypi.org/project/types-aiobotocore-alexaforbusiness/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[alexaforbusiness]'

# Lite version does not provide session.create_client overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[alexaforbusiness]'

# standalone installation
pip install types-aiobotocore-alexaforbusiness
```

- [Type annotations for aiobotocore AlexaForBusiness module](#type-annotations-for-aiobotocore-alexaforbusiness-module)
  - [AlexaForBusinessClient](#alexaforbusinessclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="alexaforbusinessclient"></a>

## AlexaForBusinessClient

Type annotations for `session.create_client("alexaforbusiness")` as
[AlexaForBusinessClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_alexaforbusiness.client import AlexaForBusinessClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [approve_skill](./client.md#approve_skill)
- [associate_contact_with_address_book](./client.md#associate_contact_with_address_book)
- [associate_device_with_network_profile](./client.md#associate_device_with_network_profile)
- [associate_device_with_room](./client.md#associate_device_with_room)
- [associate_skill_group_with_room](./client.md#associate_skill_group_with_room)
- [associate_skill_with_skill_group](./client.md#associate_skill_with_skill_group)
- [associate_skill_with_users](./client.md#associate_skill_with_users)
- [can_paginate](./client.md#can_paginate)
- [create_address_book](./client.md#create_address_book)
- [create_business_report_schedule](./client.md#create_business_report_schedule)
- [create_conference_provider](./client.md#create_conference_provider)
- [create_contact](./client.md#create_contact)
- [create_gateway_group](./client.md#create_gateway_group)
- [create_network_profile](./client.md#create_network_profile)
- [create_profile](./client.md#create_profile)
- [create_room](./client.md#create_room)
- [create_skill_group](./client.md#create_skill_group)
- [create_user](./client.md#create_user)
- [delete_address_book](./client.md#delete_address_book)
- [delete_business_report_schedule](./client.md#delete_business_report_schedule)
- [delete_conference_provider](./client.md#delete_conference_provider)
- [delete_contact](./client.md#delete_contact)
- [delete_device](./client.md#delete_device)
- [delete_device_usage_data](./client.md#delete_device_usage_data)
- [delete_gateway_group](./client.md#delete_gateway_group)
- [delete_network_profile](./client.md#delete_network_profile)
- [delete_profile](./client.md#delete_profile)
- [delete_room](./client.md#delete_room)
- [delete_room_skill_parameter](./client.md#delete_room_skill_parameter)
- [delete_skill_authorization](./client.md#delete_skill_authorization)
- [delete_skill_group](./client.md#delete_skill_group)
- [delete_user](./client.md#delete_user)
- [disassociate_contact_from_address_book](./client.md#disassociate_contact_from_address_book)
- [disassociate_device_from_room](./client.md#disassociate_device_from_room)
- [disassociate_skill_from_skill_group](./client.md#disassociate_skill_from_skill_group)
- [disassociate_skill_from_users](./client.md#disassociate_skill_from_users)
- [disassociate_skill_group_from_room](./client.md#disassociate_skill_group_from_room)
- [exceptions](./client.md#exceptions)
- [forget_smart_home_appliances](./client.md#forget_smart_home_appliances)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_address_book](./client.md#get_address_book)
- [get_conference_preference](./client.md#get_conference_preference)
- [get_conference_provider](./client.md#get_conference_provider)
- [get_contact](./client.md#get_contact)
- [get_device](./client.md#get_device)
- [get_gateway](./client.md#get_gateway)
- [get_gateway_group](./client.md#get_gateway_group)
- [get_invitation_configuration](./client.md#get_invitation_configuration)
- [get_network_profile](./client.md#get_network_profile)
- [get_paginator](./client.md#get_paginator)
- [get_profile](./client.md#get_profile)
- [get_room](./client.md#get_room)
- [get_room_skill_parameter](./client.md#get_room_skill_parameter)
- [get_skill_group](./client.md#get_skill_group)
- [list_business_report_schedules](./client.md#list_business_report_schedules)
- [list_conference_providers](./client.md#list_conference_providers)
- [list_device_events](./client.md#list_device_events)
- [list_gateway_groups](./client.md#list_gateway_groups)
- [list_gateways](./client.md#list_gateways)
- [list_skills](./client.md#list_skills)
- [list_skills_store_categories](./client.md#list_skills_store_categories)
- [list_skills_store_skills_by_category](./client.md#list_skills_store_skills_by_category)
- [list_smart_home_appliances](./client.md#list_smart_home_appliances)
- [list_tags](./client.md#list_tags)
- [put_conference_preference](./client.md#put_conference_preference)
- [put_invitation_configuration](./client.md#put_invitation_configuration)
- [put_room_skill_parameter](./client.md#put_room_skill_parameter)
- [put_skill_authorization](./client.md#put_skill_authorization)
- [register_avs_device](./client.md#register_avs_device)
- [reject_skill](./client.md#reject_skill)
- [resolve_room](./client.md#resolve_room)
- [revoke_invitation](./client.md#revoke_invitation)
- [search_address_books](./client.md#search_address_books)
- [search_contacts](./client.md#search_contacts)
- [search_devices](./client.md#search_devices)
- [search_network_profiles](./client.md#search_network_profiles)
- [search_profiles](./client.md#search_profiles)
- [search_rooms](./client.md#search_rooms)
- [search_skill_groups](./client.md#search_skill_groups)
- [search_users](./client.md#search_users)
- [send_announcement](./client.md#send_announcement)
- [send_invitation](./client.md#send_invitation)
- [start_device_sync](./client.md#start_device_sync)
- [start_smart_home_appliance_discovery](./client.md#start_smart_home_appliance_discovery)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_address_book](./client.md#update_address_book)
- [update_business_report_schedule](./client.md#update_business_report_schedule)
- [update_conference_provider](./client.md#update_conference_provider)
- [update_contact](./client.md#update_contact)
- [update_device](./client.md#update_device)
- [update_gateway](./client.md#update_gateway)
- [update_gateway_group](./client.md#update_gateway_group)
- [update_network_profile](./client.md#update_network_profile)
- [update_profile](./client.md#update_profile)
- [update_room](./client.md#update_room)
- [update_skill_group](./client.md#update_skill_group)

<a id="exceptions"></a>

### Exceptions

AlexaForBusinessClient [exceptions](./client.md#exceptions)

- AlreadyExistsException
- ClientError
- ConcurrentModificationException
- DeviceNotRegisteredException
- InvalidCertificateAuthorityException
- InvalidDeviceException
- InvalidSecretsManagerResourceException
- InvalidServiceLinkedRoleStateException
- InvalidUserStatusException
- LimitExceededException
- NameInUseException
- NotFoundException
- ResourceAssociatedException
- ResourceInUseException
- SkillNotLinkedException
- UnauthorizedException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("alexaforbusiness").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_alexaforbusiness.paginator import ListBusinessReportSchedulesPaginator, ...
```

- [ListBusinessReportSchedulesPaginator](./paginators.md#listbusinessreportschedulespaginator)
- [ListConferenceProvidersPaginator](./paginators.md#listconferenceproviderspaginator)
- [ListDeviceEventsPaginator](./paginators.md#listdeviceeventspaginator)
- [ListSkillsPaginator](./paginators.md#listskillspaginator)
- [ListSkillsStoreCategoriesPaginator](./paginators.md#listskillsstorecategoriespaginator)
- [ListSkillsStoreSkillsByCategoryPaginator](./paginators.md#listskillsstoreskillsbycategorypaginator)
- [ListSmartHomeAppliancesPaginator](./paginators.md#listsmarthomeappliancespaginator)
- [ListTagsPaginator](./paginators.md#listtagspaginator)
- [SearchDevicesPaginator](./paginators.md#searchdevicespaginator)
- [SearchProfilesPaginator](./paginators.md#searchprofilespaginator)
- [SearchRoomsPaginator](./paginators.md#searchroomspaginator)
- [SearchSkillGroupsPaginator](./paginators.md#searchskillgroupspaginator)
- [SearchUsersPaginator](./paginators.md#searchuserspaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_alexaforbusiness.literals import BusinessReportFailureCodeType, ...
```

- [BusinessReportFailureCodeType](./literals.md#businessreportfailurecodetype)
- [BusinessReportFormatType](./literals.md#businessreportformattype)
- [BusinessReportIntervalType](./literals.md#businessreportintervaltype)
- [BusinessReportStatusType](./literals.md#businessreportstatustype)
- [CommsProtocolType](./literals.md#commsprotocoltype)
- [ConferenceProviderTypeType](./literals.md#conferenceprovidertypetype)
- [ConnectionStatusType](./literals.md#connectionstatustype)
- [DeviceEventTypeType](./literals.md#deviceeventtypetype)
- [DeviceStatusDetailCodeType](./literals.md#devicestatusdetailcodetype)
- [DeviceStatusType](./literals.md#devicestatustype)
- [DeviceUsageTypeType](./literals.md#deviceusagetypetype)
- [DistanceUnitType](./literals.md#distanceunittype)
- [EnablementTypeFilterType](./literals.md#enablementtypefiltertype)
- [EnablementTypeType](./literals.md#enablementtypetype)
- [EndOfMeetingReminderTypeType](./literals.md#endofmeetingremindertypetype)
- [EnrollmentStatusType](./literals.md#enrollmentstatustype)
- [FeatureType](./literals.md#featuretype)
- [ListBusinessReportSchedulesPaginatorName](./literals.md#listbusinessreportschedulespaginatorname)
- [ListConferenceProvidersPaginatorName](./literals.md#listconferenceproviderspaginatorname)
- [ListDeviceEventsPaginatorName](./literals.md#listdeviceeventspaginatorname)
- [ListSkillsPaginatorName](./literals.md#listskillspaginatorname)
- [ListSkillsStoreCategoriesPaginatorName](./literals.md#listskillsstorecategoriespaginatorname)
- [ListSkillsStoreSkillsByCategoryPaginatorName](./literals.md#listskillsstoreskillsbycategorypaginatorname)
- [ListSmartHomeAppliancesPaginatorName](./literals.md#listsmarthomeappliancespaginatorname)
- [ListTagsPaginatorName](./literals.md#listtagspaginatorname)
- [LocaleType](./literals.md#localetype)
- [NetworkEapMethodType](./literals.md#networkeapmethodtype)
- [NetworkSecurityTypeType](./literals.md#networksecuritytypetype)
- [PhoneNumberTypeType](./literals.md#phonenumbertypetype)
- [RequirePinType](./literals.md#requirepintype)
- [SearchDevicesPaginatorName](./literals.md#searchdevicespaginatorname)
- [SearchProfilesPaginatorName](./literals.md#searchprofilespaginatorname)
- [SearchRoomsPaginatorName](./literals.md#searchroomspaginatorname)
- [SearchSkillGroupsPaginatorName](./literals.md#searchskillgroupspaginatorname)
- [SearchUsersPaginatorName](./literals.md#searchuserspaginatorname)
- [SipTypeType](./literals.md#siptypetype)
- [SkillTypeFilterType](./literals.md#skilltypefiltertype)
- [SkillTypeType](./literals.md#skilltypetype)
- [SortValueType](./literals.md#sortvaluetype)
- [TemperatureUnitType](./literals.md#temperatureunittype)
- [WakeWordType](./literals.md#wakewordtype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_alexaforbusiness.type_defs import AddressBookDataTypeDef, ...
```

- [AddressBookDataTypeDef](./type_defs.md#addressbookdatatypedef)
- [AddressBookTypeDef](./type_defs.md#addressbooktypedef)
- [ApproveSkillRequestRequestTypeDef](./type_defs.md#approveskillrequestrequesttypedef)
- [AssociateContactWithAddressBookRequestRequestTypeDef](./type_defs.md#associatecontactwithaddressbookrequestrequesttypedef)
- [AssociateDeviceWithNetworkProfileRequestRequestTypeDef](./type_defs.md#associatedevicewithnetworkprofilerequestrequesttypedef)
- [AssociateDeviceWithRoomRequestRequestTypeDef](./type_defs.md#associatedevicewithroomrequestrequesttypedef)
- [AssociateSkillGroupWithRoomRequestRequestTypeDef](./type_defs.md#associateskillgroupwithroomrequestrequesttypedef)
- [AssociateSkillWithSkillGroupRequestRequestTypeDef](./type_defs.md#associateskillwithskillgrouprequestrequesttypedef)
- [AssociateSkillWithUsersRequestRequestTypeDef](./type_defs.md#associateskillwithusersrequestrequesttypedef)
- [AudioTypeDef](./type_defs.md#audiotypedef)
- [BusinessReportContentRangeTypeDef](./type_defs.md#businessreportcontentrangetypedef)
- [BusinessReportRecurrenceTypeDef](./type_defs.md#businessreportrecurrencetypedef)
- [BusinessReportS3LocationTypeDef](./type_defs.md#businessreports3locationtypedef)
- [BusinessReportScheduleTypeDef](./type_defs.md#businessreportscheduletypedef)
- [BusinessReportTypeDef](./type_defs.md#businessreporttypedef)
- [CategoryTypeDef](./type_defs.md#categorytypedef)
- [ConferencePreferenceTypeDef](./type_defs.md#conferencepreferencetypedef)
- [ConferenceProviderTypeDef](./type_defs.md#conferenceprovidertypedef)
- [ContactDataTypeDef](./type_defs.md#contactdatatypedef)
- [ContactTypeDef](./type_defs.md#contacttypedef)
- [ContentTypeDef](./type_defs.md#contenttypedef)
- [CreateAddressBookRequestRequestTypeDef](./type_defs.md#createaddressbookrequestrequesttypedef)
- [CreateAddressBookResponseTypeDef](./type_defs.md#createaddressbookresponsetypedef)
- [CreateBusinessReportScheduleRequestRequestTypeDef](./type_defs.md#createbusinessreportschedulerequestrequesttypedef)
- [CreateBusinessReportScheduleResponseTypeDef](./type_defs.md#createbusinessreportscheduleresponsetypedef)
- [CreateConferenceProviderRequestRequestTypeDef](./type_defs.md#createconferenceproviderrequestrequesttypedef)
- [CreateConferenceProviderResponseTypeDef](./type_defs.md#createconferenceproviderresponsetypedef)
- [CreateContactRequestRequestTypeDef](./type_defs.md#createcontactrequestrequesttypedef)
- [CreateContactResponseTypeDef](./type_defs.md#createcontactresponsetypedef)
- [CreateEndOfMeetingReminderTypeDef](./type_defs.md#createendofmeetingremindertypedef)
- [CreateGatewayGroupRequestRequestTypeDef](./type_defs.md#creategatewaygrouprequestrequesttypedef)
- [CreateGatewayGroupResponseTypeDef](./type_defs.md#creategatewaygroupresponsetypedef)
- [CreateInstantBookingTypeDef](./type_defs.md#createinstantbookingtypedef)
- [CreateMeetingRoomConfigurationTypeDef](./type_defs.md#createmeetingroomconfigurationtypedef)
- [CreateNetworkProfileRequestRequestTypeDef](./type_defs.md#createnetworkprofilerequestrequesttypedef)
- [CreateNetworkProfileResponseTypeDef](./type_defs.md#createnetworkprofileresponsetypedef)
- [CreateProfileRequestRequestTypeDef](./type_defs.md#createprofilerequestrequesttypedef)
- [CreateProfileResponseTypeDef](./type_defs.md#createprofileresponsetypedef)
- [CreateRequireCheckInTypeDef](./type_defs.md#createrequirecheckintypedef)
- [CreateRoomRequestRequestTypeDef](./type_defs.md#createroomrequestrequesttypedef)
- [CreateRoomResponseTypeDef](./type_defs.md#createroomresponsetypedef)
- [CreateSkillGroupRequestRequestTypeDef](./type_defs.md#createskillgrouprequestrequesttypedef)
- [CreateSkillGroupResponseTypeDef](./type_defs.md#createskillgroupresponsetypedef)
- [CreateUserRequestRequestTypeDef](./type_defs.md#createuserrequestrequesttypedef)
- [CreateUserResponseTypeDef](./type_defs.md#createuserresponsetypedef)
- [DeleteAddressBookRequestRequestTypeDef](./type_defs.md#deleteaddressbookrequestrequesttypedef)
- [DeleteBusinessReportScheduleRequestRequestTypeDef](./type_defs.md#deletebusinessreportschedulerequestrequesttypedef)
- [DeleteConferenceProviderRequestRequestTypeDef](./type_defs.md#deleteconferenceproviderrequestrequesttypedef)
- [DeleteContactRequestRequestTypeDef](./type_defs.md#deletecontactrequestrequesttypedef)
- [DeleteDeviceRequestRequestTypeDef](./type_defs.md#deletedevicerequestrequesttypedef)
- [DeleteDeviceUsageDataRequestRequestTypeDef](./type_defs.md#deletedeviceusagedatarequestrequesttypedef)
- [DeleteGatewayGroupRequestRequestTypeDef](./type_defs.md#deletegatewaygrouprequestrequesttypedef)
- [DeleteNetworkProfileRequestRequestTypeDef](./type_defs.md#deletenetworkprofilerequestrequesttypedef)
- [DeleteProfileRequestRequestTypeDef](./type_defs.md#deleteprofilerequestrequesttypedef)
- [DeleteRoomRequestRequestTypeDef](./type_defs.md#deleteroomrequestrequesttypedef)
- [DeleteRoomSkillParameterRequestRequestTypeDef](./type_defs.md#deleteroomskillparameterrequestrequesttypedef)
- [DeleteSkillAuthorizationRequestRequestTypeDef](./type_defs.md#deleteskillauthorizationrequestrequesttypedef)
- [DeleteSkillGroupRequestRequestTypeDef](./type_defs.md#deleteskillgrouprequestrequesttypedef)
- [DeleteUserRequestRequestTypeDef](./type_defs.md#deleteuserrequestrequesttypedef)
- [DeveloperInfoTypeDef](./type_defs.md#developerinfotypedef)
- [DeviceDataTypeDef](./type_defs.md#devicedatatypedef)
- [DeviceEventTypeDef](./type_defs.md#deviceeventtypedef)
- [DeviceNetworkProfileInfoTypeDef](./type_defs.md#devicenetworkprofileinfotypedef)
- [DeviceStatusDetailTypeDef](./type_defs.md#devicestatusdetailtypedef)
- [DeviceStatusInfoTypeDef](./type_defs.md#devicestatusinfotypedef)
- [DeviceTypeDef](./type_defs.md#devicetypedef)
- [DisassociateContactFromAddressBookRequestRequestTypeDef](./type_defs.md#disassociatecontactfromaddressbookrequestrequesttypedef)
- [DisassociateDeviceFromRoomRequestRequestTypeDef](./type_defs.md#disassociatedevicefromroomrequestrequesttypedef)
- [DisassociateSkillFromSkillGroupRequestRequestTypeDef](./type_defs.md#disassociateskillfromskillgrouprequestrequesttypedef)
- [DisassociateSkillFromUsersRequestRequestTypeDef](./type_defs.md#disassociateskillfromusersrequestrequesttypedef)
- [DisassociateSkillGroupFromRoomRequestRequestTypeDef](./type_defs.md#disassociateskillgroupfromroomrequestrequesttypedef)
- [EndOfMeetingReminderTypeDef](./type_defs.md#endofmeetingremindertypedef)
- [FilterTypeDef](./type_defs.md#filtertypedef)
- [ForgetSmartHomeAppliancesRequestRequestTypeDef](./type_defs.md#forgetsmarthomeappliancesrequestrequesttypedef)
- [GatewayGroupSummaryTypeDef](./type_defs.md#gatewaygroupsummarytypedef)
- [GatewayGroupTypeDef](./type_defs.md#gatewaygrouptypedef)
- [GatewaySummaryTypeDef](./type_defs.md#gatewaysummarytypedef)
- [GatewayTypeDef](./type_defs.md#gatewaytypedef)
- [GetAddressBookRequestRequestTypeDef](./type_defs.md#getaddressbookrequestrequesttypedef)
- [GetAddressBookResponseTypeDef](./type_defs.md#getaddressbookresponsetypedef)
- [GetConferencePreferenceResponseTypeDef](./type_defs.md#getconferencepreferenceresponsetypedef)
- [GetConferenceProviderRequestRequestTypeDef](./type_defs.md#getconferenceproviderrequestrequesttypedef)
- [GetConferenceProviderResponseTypeDef](./type_defs.md#getconferenceproviderresponsetypedef)
- [GetContactRequestRequestTypeDef](./type_defs.md#getcontactrequestrequesttypedef)
- [GetContactResponseTypeDef](./type_defs.md#getcontactresponsetypedef)
- [GetDeviceRequestRequestTypeDef](./type_defs.md#getdevicerequestrequesttypedef)
- [GetDeviceResponseTypeDef](./type_defs.md#getdeviceresponsetypedef)
- [GetGatewayGroupRequestRequestTypeDef](./type_defs.md#getgatewaygrouprequestrequesttypedef)
- [GetGatewayGroupResponseTypeDef](./type_defs.md#getgatewaygroupresponsetypedef)
- [GetGatewayRequestRequestTypeDef](./type_defs.md#getgatewayrequestrequesttypedef)
- [GetGatewayResponseTypeDef](./type_defs.md#getgatewayresponsetypedef)
- [GetInvitationConfigurationResponseTypeDef](./type_defs.md#getinvitationconfigurationresponsetypedef)
- [GetNetworkProfileRequestRequestTypeDef](./type_defs.md#getnetworkprofilerequestrequesttypedef)
- [GetNetworkProfileResponseTypeDef](./type_defs.md#getnetworkprofileresponsetypedef)
- [GetProfileRequestRequestTypeDef](./type_defs.md#getprofilerequestrequesttypedef)
- [GetProfileResponseTypeDef](./type_defs.md#getprofileresponsetypedef)
- [GetRoomRequestRequestTypeDef](./type_defs.md#getroomrequestrequesttypedef)
- [GetRoomResponseTypeDef](./type_defs.md#getroomresponsetypedef)
- [GetRoomSkillParameterRequestRequestTypeDef](./type_defs.md#getroomskillparameterrequestrequesttypedef)
- [GetRoomSkillParameterResponseTypeDef](./type_defs.md#getroomskillparameterresponsetypedef)
- [GetSkillGroupRequestRequestTypeDef](./type_defs.md#getskillgrouprequestrequesttypedef)
- [GetSkillGroupResponseTypeDef](./type_defs.md#getskillgroupresponsetypedef)
- [IPDialInTypeDef](./type_defs.md#ipdialintypedef)
- [InstantBookingTypeDef](./type_defs.md#instantbookingtypedef)
- [ListBusinessReportSchedulesRequestRequestTypeDef](./type_defs.md#listbusinessreportschedulesrequestrequesttypedef)
- [ListBusinessReportSchedulesResponseTypeDef](./type_defs.md#listbusinessreportschedulesresponsetypedef)
- [ListConferenceProvidersRequestRequestTypeDef](./type_defs.md#listconferenceprovidersrequestrequesttypedef)
- [ListConferenceProvidersResponseTypeDef](./type_defs.md#listconferenceprovidersresponsetypedef)
- [ListDeviceEventsRequestRequestTypeDef](./type_defs.md#listdeviceeventsrequestrequesttypedef)
- [ListDeviceEventsResponseTypeDef](./type_defs.md#listdeviceeventsresponsetypedef)
- [ListGatewayGroupsRequestRequestTypeDef](./type_defs.md#listgatewaygroupsrequestrequesttypedef)
- [ListGatewayGroupsResponseTypeDef](./type_defs.md#listgatewaygroupsresponsetypedef)
- [ListGatewaysRequestRequestTypeDef](./type_defs.md#listgatewaysrequestrequesttypedef)
- [ListGatewaysResponseTypeDef](./type_defs.md#listgatewaysresponsetypedef)
- [ListSkillsRequestRequestTypeDef](./type_defs.md#listskillsrequestrequesttypedef)
- [ListSkillsResponseTypeDef](./type_defs.md#listskillsresponsetypedef)
- [ListSkillsStoreCategoriesRequestRequestTypeDef](./type_defs.md#listskillsstorecategoriesrequestrequesttypedef)
- [ListSkillsStoreCategoriesResponseTypeDef](./type_defs.md#listskillsstorecategoriesresponsetypedef)
- [ListSkillsStoreSkillsByCategoryRequestRequestTypeDef](./type_defs.md#listskillsstoreskillsbycategoryrequestrequesttypedef)
- [ListSkillsStoreSkillsByCategoryResponseTypeDef](./type_defs.md#listskillsstoreskillsbycategoryresponsetypedef)
- [ListSmartHomeAppliancesRequestRequestTypeDef](./type_defs.md#listsmarthomeappliancesrequestrequesttypedef)
- [ListSmartHomeAppliancesResponseTypeDef](./type_defs.md#listsmarthomeappliancesresponsetypedef)
- [ListTagsRequestRequestTypeDef](./type_defs.md#listtagsrequestrequesttypedef)
- [ListTagsResponseTypeDef](./type_defs.md#listtagsresponsetypedef)
- [MeetingRoomConfigurationTypeDef](./type_defs.md#meetingroomconfigurationtypedef)
- [MeetingSettingTypeDef](./type_defs.md#meetingsettingtypedef)
- [NetworkProfileDataTypeDef](./type_defs.md#networkprofiledatatypedef)
- [NetworkProfileTypeDef](./type_defs.md#networkprofiletypedef)
- [PSTNDialInTypeDef](./type_defs.md#pstndialintypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PhoneNumberTypeDef](./type_defs.md#phonenumbertypedef)
- [ProfileDataTypeDef](./type_defs.md#profiledatatypedef)
- [ProfileTypeDef](./type_defs.md#profiletypedef)
- [PutConferencePreferenceRequestRequestTypeDef](./type_defs.md#putconferencepreferencerequestrequesttypedef)
- [PutInvitationConfigurationRequestRequestTypeDef](./type_defs.md#putinvitationconfigurationrequestrequesttypedef)
- [PutRoomSkillParameterRequestRequestTypeDef](./type_defs.md#putroomskillparameterrequestrequesttypedef)
- [PutSkillAuthorizationRequestRequestTypeDef](./type_defs.md#putskillauthorizationrequestrequesttypedef)
- [RegisterAVSDeviceRequestRequestTypeDef](./type_defs.md#registeravsdevicerequestrequesttypedef)
- [RegisterAVSDeviceResponseTypeDef](./type_defs.md#registeravsdeviceresponsetypedef)
- [RejectSkillRequestRequestTypeDef](./type_defs.md#rejectskillrequestrequesttypedef)
- [RequireCheckInTypeDef](./type_defs.md#requirecheckintypedef)
- [ResolveRoomRequestRequestTypeDef](./type_defs.md#resolveroomrequestrequesttypedef)
- [ResolveRoomResponseTypeDef](./type_defs.md#resolveroomresponsetypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RevokeInvitationRequestRequestTypeDef](./type_defs.md#revokeinvitationrequestrequesttypedef)
- [RoomDataTypeDef](./type_defs.md#roomdatatypedef)
- [RoomSkillParameterTypeDef](./type_defs.md#roomskillparametertypedef)
- [RoomTypeDef](./type_defs.md#roomtypedef)
- [SearchAddressBooksRequestRequestTypeDef](./type_defs.md#searchaddressbooksrequestrequesttypedef)
- [SearchAddressBooksResponseTypeDef](./type_defs.md#searchaddressbooksresponsetypedef)
- [SearchContactsRequestRequestTypeDef](./type_defs.md#searchcontactsrequestrequesttypedef)
- [SearchContactsResponseTypeDef](./type_defs.md#searchcontactsresponsetypedef)
- [SearchDevicesRequestRequestTypeDef](./type_defs.md#searchdevicesrequestrequesttypedef)
- [SearchDevicesResponseTypeDef](./type_defs.md#searchdevicesresponsetypedef)
- [SearchNetworkProfilesRequestRequestTypeDef](./type_defs.md#searchnetworkprofilesrequestrequesttypedef)
- [SearchNetworkProfilesResponseTypeDef](./type_defs.md#searchnetworkprofilesresponsetypedef)
- [SearchProfilesRequestRequestTypeDef](./type_defs.md#searchprofilesrequestrequesttypedef)
- [SearchProfilesResponseTypeDef](./type_defs.md#searchprofilesresponsetypedef)
- [SearchRoomsRequestRequestTypeDef](./type_defs.md#searchroomsrequestrequesttypedef)
- [SearchRoomsResponseTypeDef](./type_defs.md#searchroomsresponsetypedef)
- [SearchSkillGroupsRequestRequestTypeDef](./type_defs.md#searchskillgroupsrequestrequesttypedef)
- [SearchSkillGroupsResponseTypeDef](./type_defs.md#searchskillgroupsresponsetypedef)
- [SearchUsersRequestRequestTypeDef](./type_defs.md#searchusersrequestrequesttypedef)
- [SearchUsersResponseTypeDef](./type_defs.md#searchusersresponsetypedef)
- [SendAnnouncementRequestRequestTypeDef](./type_defs.md#sendannouncementrequestrequesttypedef)
- [SendAnnouncementResponseTypeDef](./type_defs.md#sendannouncementresponsetypedef)
- [SendInvitationRequestRequestTypeDef](./type_defs.md#sendinvitationrequestrequesttypedef)
- [SipAddressTypeDef](./type_defs.md#sipaddresstypedef)
- [SkillDetailsTypeDef](./type_defs.md#skilldetailstypedef)
- [SkillGroupDataTypeDef](./type_defs.md#skillgroupdatatypedef)
- [SkillGroupTypeDef](./type_defs.md#skillgrouptypedef)
- [SkillSummaryTypeDef](./type_defs.md#skillsummarytypedef)
- [SkillsStoreSkillTypeDef](./type_defs.md#skillsstoreskilltypedef)
- [SmartHomeApplianceTypeDef](./type_defs.md#smarthomeappliancetypedef)
- [SortTypeDef](./type_defs.md#sorttypedef)
- [SsmlTypeDef](./type_defs.md#ssmltypedef)
- [StartDeviceSyncRequestRequestTypeDef](./type_defs.md#startdevicesyncrequestrequesttypedef)
- [StartSmartHomeApplianceDiscoveryRequestRequestTypeDef](./type_defs.md#startsmarthomeappliancediscoveryrequestrequesttypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TextTypeDef](./type_defs.md#texttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateAddressBookRequestRequestTypeDef](./type_defs.md#updateaddressbookrequestrequesttypedef)
- [UpdateBusinessReportScheduleRequestRequestTypeDef](./type_defs.md#updatebusinessreportschedulerequestrequesttypedef)
- [UpdateConferenceProviderRequestRequestTypeDef](./type_defs.md#updateconferenceproviderrequestrequesttypedef)
- [UpdateContactRequestRequestTypeDef](./type_defs.md#updatecontactrequestrequesttypedef)
- [UpdateDeviceRequestRequestTypeDef](./type_defs.md#updatedevicerequestrequesttypedef)
- [UpdateEndOfMeetingReminderTypeDef](./type_defs.md#updateendofmeetingremindertypedef)
- [UpdateGatewayGroupRequestRequestTypeDef](./type_defs.md#updategatewaygrouprequestrequesttypedef)
- [UpdateGatewayRequestRequestTypeDef](./type_defs.md#updategatewayrequestrequesttypedef)
- [UpdateInstantBookingTypeDef](./type_defs.md#updateinstantbookingtypedef)
- [UpdateMeetingRoomConfigurationTypeDef](./type_defs.md#updatemeetingroomconfigurationtypedef)
- [UpdateNetworkProfileRequestRequestTypeDef](./type_defs.md#updatenetworkprofilerequestrequesttypedef)
- [UpdateProfileRequestRequestTypeDef](./type_defs.md#updateprofilerequestrequesttypedef)
- [UpdateRequireCheckInTypeDef](./type_defs.md#updaterequirecheckintypedef)
- [UpdateRoomRequestRequestTypeDef](./type_defs.md#updateroomrequestrequesttypedef)
- [UpdateSkillGroupRequestRequestTypeDef](./type_defs.md#updateskillgrouprequestrequesttypedef)
- [UserDataTypeDef](./type_defs.md#userdatatypedef)
