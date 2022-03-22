<a id="snsserviceresource-for-aiobotocore-sns-module"></a>

# SNSServiceResource for aiobotocore SNS module

> [Index](../README.md) > [SNS](./README.md) > SNSServiceResource

Auto-generated documentation for
[SNS](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS)
type annotations stubs module
[types-aiobotocore-sns](https://pypi.org/project/types-aiobotocore-sns/).

- [SNSServiceResource for aiobotocore SNS module](#snsserviceresource-for-aiobotocore-sns-module)
  - [SNSServiceResource](#snsserviceresource)
  - [Attributes](#attributes)
  - [Collections](#collections)
    - [ServiceResourcePlatformApplicationsCollection](#serviceresourceplatformapplicationscollection)
    - [ServiceResourceSubscriptionsCollection](#serviceresourcesubscriptionscollection)
    - [ServiceResourceTopicsCollection](#serviceresourcetopicscollection)
  - [Methods](#methods)
    - [SNSServiceResource.PlatformApplication method](#snsserviceresourceplatformapplication-method)
    - [SNSServiceResource.PlatformEndpoint method](#snsserviceresourceplatformendpoint-method)
    - [SNSServiceResource.Subscription method](#snsserviceresourcesubscription-method)
    - [SNSServiceResource.Topic method](#snsserviceresourcetopic-method)
    - [SNSServiceResource.create_platform_application method](#snsserviceresourcecreate_platform_application-method)
    - [SNSServiceResource.create_topic method](#snsserviceresourcecreate_topic-method)
    - [SNSServiceResource.get_available_subresources method](#snsserviceresourceget_available_subresources-method)
  - [PlatformApplication](#platformapplication)
    - [PlatformApplication attributes](#platformapplication-attributes)
    - [PlatformApplication collections](#platformapplication-collections)
    - [PlatformApplication methods](#platformapplication-methods)
  - [PlatformEndpoint](#platformendpoint)
    - [PlatformEndpoint attributes](#platformendpoint-attributes)
    - [PlatformEndpoint methods](#platformendpoint-methods)
  - [Subscription](#subscription)
    - [Subscription attributes](#subscription-attributes)
    - [Subscription methods](#subscription-methods)
  - [Topic](#topic)
    - [Topic attributes](#topic-attributes)
    - [Topic collections](#topic-collections)
    - [Topic methods](#topic-methods)

<a id="snsserviceresource"></a>

## SNSServiceResource

Type annotations for `aiobotocore.resource("sns")`, included resources and
collections.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import SNSServiceResource

def get_sns_resource() -> SNSServiceResource:
    return boto3.resource("sns")
```

Boto3 documentation:
[SNS.ServiceResource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource)

<a id="attributes"></a>

## Attributes

- `meta`: [SNSResourceMeta](#snsresourcemeta)

- `platform_applications`:
  [ServiceResourcePlatformApplicationsCollection](#serviceresourceplatformapplicationscollection)

- `subscriptions`:
  [ServiceResourceSubscriptionsCollection](#serviceresourcesubscriptionscollection)

- `topics`: [ServiceResourceTopicsCollection](#serviceresourcetopicscollection)

<a id="collections"></a>

## Collections

<a id="serviceresourceplatformapplicationscollection"></a>

### ServiceResourcePlatformApplicationsCollection

Type annotations for `boto3.resource("sns").platform_applications` collection.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import ServiceResourcePlatformApplicationsCollection,

def get_collection() -> ServiceResourcePlatformApplicationsCollection:
    return boto3.resource("sns").platform_applications
```

Provides access to [PlatformApplication](#platformapplication) resource.

Boto3 documentation:
[SNS.ServiceResource.platform_applications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.platform_applications)

<a id="serviceresourcesubscriptionscollection"></a>

### ServiceResourceSubscriptionsCollection

Type annotations for `boto3.resource("sns").subscriptions` collection.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import ServiceResourceSubscriptionsCollection,

def get_collection() -> ServiceResourceSubscriptionsCollection:
    return boto3.resource("sns").subscriptions
```

Provides access to [Subscription](#subscription) resource.

Boto3 documentation:
[SNS.ServiceResource.subscriptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.subscriptions)

<a id="serviceresourcetopicscollection"></a>

### ServiceResourceTopicsCollection

Type annotations for `boto3.resource("sns").topics` collection.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import ServiceResourceTopicsCollection,

def get_collection() -> ServiceResourceTopicsCollection:
    return boto3.resource("sns").topics
```

Provides access to [Topic](#topic) resource.

Boto3 documentation:
[SNS.ServiceResource.topics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.topics)

<a id="methods"></a>

## Methods

<a id="snsserviceresourceplatformapplication-method"></a>

### SNSServiceResource.PlatformApplication method

Creates a PlatformApplication resource.

Type annotations for `aiobotocore.resource("sns").PlatformApplication` method.

Boto3 documentation:
[SNS.ServiceResource.PlatformApplication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.PlatformApplication)

Asynchronous method. Use `await PlatformApplication(...)` for a synchronous
call.

Arguments mapping described in
[ServiceResourcePlatformApplicationRequestTypeDef](./type_defs.md#serviceresourceplatformapplicationrequesttypedef).

Arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for [PlatformApplication](#platformapplication).

<a id="snsserviceresourceplatformendpoint-method"></a>

### SNSServiceResource.PlatformEndpoint method

Creates a PlatformEndpoint resource.

Type annotations for `aiobotocore.resource("sns").PlatformEndpoint` method.

Boto3 documentation:
[SNS.ServiceResource.PlatformEndpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.PlatformEndpoint)

Asynchronous method. Use `await PlatformEndpoint(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourcePlatformEndpointRequestTypeDef](./type_defs.md#serviceresourceplatformendpointrequesttypedef).

Arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for [PlatformEndpoint](#platformendpoint).

<a id="snsserviceresourcesubscription-method"></a>

### SNSServiceResource.Subscription method

Creates a Subscription resource.

Type annotations for `aiobotocore.resource("sns").Subscription` method.

Boto3 documentation:
[SNS.ServiceResource.Subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.Subscription)

Asynchronous method. Use `await Subscription(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceSubscriptionRequestTypeDef](./type_defs.md#serviceresourcesubscriptionrequesttypedef).

Arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for [Subscription](#subscription).

<a id="snsserviceresourcetopic-method"></a>

### SNSServiceResource.Topic method

Creates a Topic resource.

Type annotations for `aiobotocore.resource("sns").Topic` method.

Boto3 documentation:
[SNS.ServiceResource.Topic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.Topic)

Asynchronous method. Use `await Topic(...)` for a synchronous call.

Arguments mapping described in
[ServiceResourceTopicRequestTypeDef](./type_defs.md#serviceresourcetopicrequesttypedef).

Arguments:

- `arn`: `str` *(required)*

Returns a `Coroutine` for [Topic](#topic).

<a id="snsserviceresourcecreate\_platform\_application-method"></a>

### SNSServiceResource.create_platform_application method

Creates a platform application object for one of the supported push
notification services, such as APNS and GCM (Firebase Cloud Messaging), to
which devices and mobile apps may register.

Type annotations for `aiobotocore.resource("sns").create_platform_application`
method.

Boto3 documentation:
[SNS.ServiceResource.create_platform_application](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.create_platform_application)

Asynchronous method. Use `await create_platform_application(...)` for a
synchronous call.

Arguments mapping described in
[CreatePlatformApplicationInputServiceResourceCreatePlatformApplicationTypeDef](./type_defs.md#createplatformapplicationinputserviceresourcecreateplatformapplicationtypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Platform`: `str` *(required)*
- `Attributes`: `Mapping`\[`str`, `str`\] *(required)*

Returns a `Coroutine` for [PlatformApplication](#platformapplication).

<a id="snsserviceresourcecreate\_topic-method"></a>

### SNSServiceResource.create_topic method

Creates a topic to which notifications can be published.

Type annotations for `aiobotocore.resource("sns").create_topic` method.

Boto3 documentation:
[SNS.ServiceResource.create_topic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.create_topic)

Asynchronous method. Use `await create_topic(...)` for a synchronous call.

Arguments mapping described in
[CreateTopicInputServiceResourceCreateTopicTypeDef](./type_defs.md#createtopicinputserviceresourcecreatetopictypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `Attributes`: `Mapping`\[`str`, `str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for [Topic](#topic).

<a id="snsserviceresourceget\_available\_subresources-method"></a>

### SNSServiceResource.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("sns").get_available_subresources`
method.

Boto3 documentation:
[SNS.ServiceResource.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="platformapplication"></a>

## PlatformApplication

Type annotations for `aiobotocore.resource("sns").PlatformApplication` class.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import PlatformApplication

def get_resource() -> PlatformApplication:
    return boto3.resource("sns").PlatformApplication(...)
```

Boto3 documentation:
[SNS.PlatformApplication](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.PlatformApplication)

<a id="platformapplication-attributes"></a>

### PlatformApplication attributes

- `attributes`: `Dict`\[`str`, `str`\]
- `arn`: `str`
- `endpoints`:
  [PlatformApplicationEndpointsCollection](#platformapplicationendpointscollection)

<a id="platformapplication-collections"></a>

### PlatformApplication collections

<a id="platformapplicationendpoints"></a>

#### PlatformApplication.endpoints

Type annotations for
`aiobotocore.resource("sns").PlatformApplication(...).endpoints` collection.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import PlatformApplicationEndpointsCollection,

def get_collection() -> PlatformApplicationEndpointsCollection:
    resource = boto3.resource("sns").PlatformApplication(...)
    return resource.endpoints
```

Provides access to [PlatformEndpoint](#platformendpoint) resource.

Boto3 documentation:
[SNS.PlatformApplication.PlatformApplicationEndpointsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.endpoints)

<a id="platformapplication-methods"></a>

### PlatformApplication methods

<a id="platformapplicationcreate\_platform\_endpoint-method"></a>

#### PlatformApplication.create_platform_endpoint method

Creates an endpoint for a device and mobile app on one of the supported push
notification services, such as GCM (Firebase Cloud Messaging) and APNS.

Type annotations for `aiobotocore.resource("sns").create_platform_endpoint`
method.

Boto3 documentation:
[SNS.PlatformApplication.create_platform_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.create_platform_endpoint)

Asynchronous method. Use `await create_platform_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[CreatePlatformEndpointInputPlatformApplicationCreatePlatformEndpointTypeDef](./type_defs.md#createplatformendpointinputplatformapplicationcreateplatformendpointtypedef).

Keyword-only arguments:

- `Token`: `str` *(required)*
- `CustomUserData`: `str`
- `Attributes`: `Mapping`\[`str`, `str`\]

Returns a `Coroutine` for [PlatformEndpoint](#platformendpoint).

<a id="platformapplicationdelete-method"></a>

#### PlatformApplication.delete method

Deletes a platform application object for one of the supported push
notification services, such as APNS and GCM (Firebase Cloud Messaging).

Type annotations for `aiobotocore.resource("sns").delete` method.

Boto3 documentation:
[SNS.PlatformApplication.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

<a id="platformapplicationget\_available\_subresources-method"></a>

#### PlatformApplication.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("sns").get_available_subresources`
method.

Boto3 documentation:
[SNS.PlatformApplication.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="platformapplicationload-method"></a>

#### PlatformApplication.load method

Calls :py:meth:`SNS.Client.get_platform_application_attributes` to update the
attributes of the PlatformApplication resource.

Type annotations for `aiobotocore.resource("sns").load` method.

Boto3 documentation:
[SNS.PlatformApplication.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="platformapplicationreload-method"></a>

#### PlatformApplication.reload method

Calls :py:meth:`SNS.Client.get_platform_application_attributes` to update the
attributes of the PlatformApplication resource.

Type annotations for `aiobotocore.resource("sns").reload` method.

Boto3 documentation:
[SNS.PlatformApplication.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="platformapplicationset\_attributes-method"></a>

#### PlatformApplication.set_attributes method

Sets the attributes of the platform application object for the supported push
notification services, such as APNS and GCM (Firebase Cloud Messaging).

Type annotations for `aiobotocore.resource("sns").set_attributes` method.

Boto3 documentation:
[SNS.PlatformApplication.set_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformApplication.set_attributes)

Asynchronous method. Use `await set_attributes(...)` for a synchronous call.

Arguments mapping described in
[SetPlatformApplicationAttributesInputPlatformApplicationSetAttributesTypeDef](./type_defs.md#setplatformapplicationattributesinputplatformapplicationsetattributestypedef).

Keyword-only arguments:

- `Attributes`: `Mapping`\[`str`, `str`\] *(required)*

<a id="platformendpoint"></a>

## PlatformEndpoint

Type annotations for `aiobotocore.resource("sns").PlatformEndpoint` class.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import PlatformEndpoint

def get_resource() -> PlatformEndpoint:
    return boto3.resource("sns").PlatformEndpoint(...)
```

Boto3 documentation:
[SNS.PlatformEndpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.PlatformEndpoint)

<a id="platformendpoint-attributes"></a>

### PlatformEndpoint attributes

- `attributes`: `Dict`\[`str`, `str`\]
- `arn`: `str`

<a id="platformendpoint-methods"></a>

### PlatformEndpoint methods

<a id="platformendpointdelete-method"></a>

#### PlatformEndpoint.delete method

Deletes the endpoint for a device and mobile app from Amazon SNS.

Type annotations for `aiobotocore.resource("sns").delete` method.

Boto3 documentation:
[SNS.PlatformEndpoint.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

<a id="platformendpointget\_available\_subresources-method"></a>

#### PlatformEndpoint.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("sns").get_available_subresources`
method.

Boto3 documentation:
[SNS.PlatformEndpoint.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="platformendpointload-method"></a>

#### PlatformEndpoint.load method

Calls :py:meth:`SNS.Client.get_endpoint_attributes` to update the attributes of
the PlatformEndpoint resource.

Type annotations for `aiobotocore.resource("sns").load` method.

Boto3 documentation:
[SNS.PlatformEndpoint.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="platformendpointpublish-method"></a>

#### PlatformEndpoint.publish method

Sends a message to an Amazon SNS topic, a text message (SMS message) directly
to a phone number, or a message to a mobile platform endpoint (when you specify
the `TargetArn` ).

Type annotations for `aiobotocore.resource("sns").publish` method.

Boto3 documentation:
[SNS.PlatformEndpoint.publish](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.publish)

Asynchronous method. Use `await publish(...)` for a synchronous call.

Arguments mapping described in
[PublishInputPlatformEndpointPublishTypeDef](./type_defs.md#publishinputplatformendpointpublishtypedef).

Keyword-only arguments:

- `Message`: `str` *(required)*
- `TopicArn`: `str`
- `PhoneNumber`: `str`
- `Subject`: `str`
- `MessageStructure`: `str`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

Returns a `Coroutine` for
[PublishResponseTypeDef](./type_defs.md#publishresponsetypedef).

<a id="platformendpointreload-method"></a>

#### PlatformEndpoint.reload method

Calls :py:meth:`SNS.Client.get_endpoint_attributes` to update the attributes of
the PlatformEndpoint resource.

Type annotations for `aiobotocore.resource("sns").reload` method.

Boto3 documentation:
[SNS.PlatformEndpoint.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="platformendpointset\_attributes-method"></a>

#### PlatformEndpoint.set_attributes method

Sets the attributes for an endpoint for a device on one of the supported push
notification services, such as GCM (Firebase Cloud Messaging) and APNS.

Type annotations for `aiobotocore.resource("sns").set_attributes` method.

Boto3 documentation:
[SNS.PlatformEndpoint.set_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.PlatformEndpoint.set_attributes)

Asynchronous method. Use `await set_attributes(...)` for a synchronous call.

Arguments mapping described in
[SetEndpointAttributesInputPlatformEndpointSetAttributesTypeDef](./type_defs.md#setendpointattributesinputplatformendpointsetattributestypedef).

Keyword-only arguments:

- `Attributes`: `Mapping`\[`str`, `str`\] *(required)*

<a id="subscription"></a>

## Subscription

Type annotations for `aiobotocore.resource("sns").Subscription` class.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import Subscription

def get_resource() -> Subscription:
    return boto3.resource("sns").Subscription(...)
```

Boto3 documentation:
[SNS.Subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.Subscription)

<a id="subscription-attributes"></a>

### Subscription attributes

- `attributes`: `Dict`\[`str`, `str`\]
- `arn`: `str`

<a id="subscription-methods"></a>

### Subscription methods

<a id="subscriptiondelete-method"></a>

#### Subscription.delete method

Deletes a subscription.

Type annotations for `aiobotocore.resource("sns").delete` method.

Boto3 documentation:
[SNS.Subscription.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Subscription.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

<a id="subscriptionget\_available\_subresources-method"></a>

#### Subscription.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("sns").get_available_subresources`
method.

Boto3 documentation:
[SNS.Subscription.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Subscription.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="subscriptionload-method"></a>

#### Subscription.load method

Calls :py:meth:`SNS.Client.get_subscription_attributes` to update the
attributes of the Subscription resource.

Type annotations for `aiobotocore.resource("sns").load` method.

Boto3 documentation:
[SNS.Subscription.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Subscription.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="subscriptionreload-method"></a>

#### Subscription.reload method

Calls :py:meth:`SNS.Client.get_subscription_attributes` to update the
attributes of the Subscription resource.

Type annotations for `aiobotocore.resource("sns").reload` method.

Boto3 documentation:
[SNS.Subscription.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Subscription.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="subscriptionset\_attributes-method"></a>

#### Subscription.set_attributes method

Allows a subscription owner to set an attribute of the subscription to a new
value.

Type annotations for `aiobotocore.resource("sns").set_attributes` method.

Boto3 documentation:
[SNS.Subscription.set_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Subscription.set_attributes)

Asynchronous method. Use `await set_attributes(...)` for a synchronous call.

Arguments mapping described in
[SetSubscriptionAttributesInputSubscriptionSetAttributesTypeDef](./type_defs.md#setsubscriptionattributesinputsubscriptionsetattributestypedef).

Keyword-only arguments:

- `AttributeName`: `str` *(required)*
- `AttributeValue`: `str`

<a id="topic"></a>

## Topic

Type annotations for `aiobotocore.resource("sns").Topic` class.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import Topic

def get_resource() -> Topic:
    return boto3.resource("sns").Topic(...)
```

Boto3 documentation:
[SNS.Topic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.ServiceResource.Topic)

<a id="topic-attributes"></a>

### Topic attributes

- `attributes`: `Dict`\[`str`, `str`\]
- `arn`: `str`
- `subscriptions`:
  [TopicSubscriptionsCollection](#topicsubscriptionscollection)

<a id="topic-collections"></a>

### Topic collections

<a id="topicsubscriptions"></a>

#### Topic.subscriptions

Type annotations for `aiobotocore.resource("sns").Topic(...).subscriptions`
collection.

Can be used directly:

```python
from types_aiobotocore_sns.service_resource import TopicSubscriptionsCollection,

def get_collection() -> TopicSubscriptionsCollection:
    resource = boto3.resource("sns").Topic(...)
    return resource.subscriptions
```

Provides access to [Subscription](#subscription) resource.

Boto3 documentation:
[SNS.Topic.TopicSubscriptionsCollection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.subscriptions)

<a id="topic-methods"></a>

### Topic methods

<a id="topicadd\_permission-method"></a>

#### Topic.add_permission method

Adds a statement to a topic's access control policy, granting access for the
specified Amazon Web Services accounts to the specified actions.

Type annotations for `aiobotocore.resource("sns").add_permission` method.

Boto3 documentation:
[SNS.Topic.add_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.add_permission)

Asynchronous method. Use `await add_permission(...)` for a synchronous call.

Arguments mapping described in
[AddPermissionInputTopicAddPermissionTypeDef](./type_defs.md#addpermissioninputtopicaddpermissiontypedef).

Keyword-only arguments:

- `Label`: `str` *(required)*
- `AWSAccountId`: `Sequence`\[`str`\] *(required)*
- `ActionName`: `Sequence`\[`str`\] *(required)*

<a id="topicconfirm\_subscription-method"></a>

#### Topic.confirm_subscription method

Verifies an endpoint owner's intent to receive messages by validating the token
sent to the endpoint by an earlier `Subscribe` action.

Type annotations for `aiobotocore.resource("sns").confirm_subscription` method.

Boto3 documentation:
[SNS.Topic.confirm_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.confirm_subscription)

Asynchronous method. Use `await confirm_subscription(...)` for a synchronous
call.

Arguments mapping described in
[ConfirmSubscriptionInputTopicConfirmSubscriptionTypeDef](./type_defs.md#confirmsubscriptioninputtopicconfirmsubscriptiontypedef).

Keyword-only arguments:

- `Token`: `str` *(required)*
- `AuthenticateOnUnsubscribe`: `str`

Returns a `Coroutine` for [Subscription](#subscription).

<a id="topicdelete-method"></a>

#### Topic.delete method

Deletes a topic and all its subscriptions.

Type annotations for `aiobotocore.resource("sns").delete` method.

Boto3 documentation:
[SNS.Topic.delete](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.delete)

Asynchronous method. Use `await delete(...)` for a synchronous call.

<a id="topicget\_available\_subresources-method"></a>

#### Topic.get_available_subresources method

Returns a list of all the available sub-resources for this Resource.

Type annotations for `aiobotocore.resource("sns").get_available_subresources`
method.

Boto3 documentation:
[SNS.Topic.get_available_subresources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.get_available_subresources)

Asynchronous method. Use `await get_available_subresources(...)` for a
synchronous call.

Returns a `Coroutine` for `Sequence`\[`str`\].

<a id="topicload-method"></a>

#### Topic.load method

Calls :py:meth:`SNS.Client.get_topic_attributes` to update the attributes of
the Topic resource.

Type annotations for `aiobotocore.resource("sns").load` method.

Boto3 documentation:
[SNS.Topic.load](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.load)

Asynchronous method. Use `await load(...)` for a synchronous call.

<a id="topicpublish-method"></a>

#### Topic.publish method

Sends a message to an Amazon SNS topic, a text message (SMS message) directly
to a phone number, or a message to a mobile platform endpoint (when you specify
the `TargetArn` ).

Type annotations for `aiobotocore.resource("sns").publish` method.

Boto3 documentation:
[SNS.Topic.publish](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.publish)

Asynchronous method. Use `await publish(...)` for a synchronous call.

Arguments mapping described in
[PublishInputTopicPublishTypeDef](./type_defs.md#publishinputtopicpublishtypedef).

Keyword-only arguments:

- `Message`: `str` *(required)*
- `TargetArn`: `str`
- `PhoneNumber`: `str`
- `Subject`: `str`
- `MessageStructure`: `str`
- `MessageAttributes`: `Mapping`\[`str`,
  [MessageAttributeValueTypeDef](./type_defs.md#messageattributevaluetypedef)\]
- `MessageDeduplicationId`: `str`
- `MessageGroupId`: `str`

Returns a `Coroutine` for
[PublishResponseTypeDef](./type_defs.md#publishresponsetypedef).

<a id="topicreload-method"></a>

#### Topic.reload method

Calls :py:meth:`SNS.Client.get_topic_attributes` to update the attributes of
the Topic resource.

Type annotations for `aiobotocore.resource("sns").reload` method.

Boto3 documentation:
[SNS.Topic.reload](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.reload)

Asynchronous method. Use `await reload(...)` for a synchronous call.

<a id="topicremove\_permission-method"></a>

#### Topic.remove_permission method

Removes a statement from a topic's access control policy.

Type annotations for `aiobotocore.resource("sns").remove_permission` method.

Boto3 documentation:
[SNS.Topic.remove_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.remove_permission)

Asynchronous method. Use `await remove_permission(...)` for a synchronous call.

Arguments mapping described in
[RemovePermissionInputTopicRemovePermissionTypeDef](./type_defs.md#removepermissioninputtopicremovepermissiontypedef).

Keyword-only arguments:

- `Label`: `str` *(required)*

<a id="topicset\_attributes-method"></a>

#### Topic.set_attributes method

Allows a topic owner to set an attribute of the topic to a new value.

Type annotations for `aiobotocore.resource("sns").set_attributes` method.

Boto3 documentation:
[SNS.Topic.set_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.set_attributes)

Asynchronous method. Use `await set_attributes(...)` for a synchronous call.

Arguments mapping described in
[SetTopicAttributesInputTopicSetAttributesTypeDef](./type_defs.md#settopicattributesinputtopicsetattributestypedef).

Keyword-only arguments:

- `AttributeName`: `str` *(required)*
- `AttributeValue`: `str`

<a id="topicsubscribe-method"></a>

#### Topic.subscribe method

Subscribes an endpoint to an Amazon SNS topic.

Type annotations for `aiobotocore.resource("sns").subscribe` method.

Boto3 documentation:
[SNS.Topic.subscribe](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Topic.subscribe)

Asynchronous method. Use `await subscribe(...)` for a synchronous call.

Arguments mapping described in
[SubscribeInputTopicSubscribeTypeDef](./type_defs.md#subscribeinputtopicsubscribetypedef).

Keyword-only arguments:

- `Protocol`: `str` *(required)*
- `Endpoint`: `str`
- `Attributes`: `Mapping`\[`str`, `str`\]
- `ReturnSubscriptionArn`: `bool`

Returns a `Coroutine` for [Subscription](#subscription).
