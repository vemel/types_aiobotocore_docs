<a id="lexmodelbuildingserviceclient-for-aiobotocore-lexmodelbuildingservice-module"></a>

# LexModelBuildingServiceClient for aiobotocore LexModelBuildingService module

> [Index](..) > [LexModelBuildingService](.) > LexModelBuildingServiceClient

Auto-generated documentation for
[LexModelBuildingService](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
type annotations stubs module
[types-aiobotocore-lex-models](https://pypi.org/project/types-aiobotocore-lex-models/).

- [LexModelBuildingServiceClient for aiobotocore LexModelBuildingService module](#lexmodelbuildingserviceclient-for-aiobotocore-lexmodelbuildingservice-module)
  - [LexModelBuildingServiceClient](#lexmodelbuildingserviceclient)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [can_paginate](#can_paginate)
    - [create_bot_version](#create_bot_version)
    - [create_intent_version](#create_intent_version)
    - [create_slot_type_version](#create_slot_type_version)
    - [delete_bot](#delete_bot)
    - [delete_bot_alias](#delete_bot_alias)
    - [delete_bot_channel_association](#delete_bot_channel_association)
    - [delete_bot_version](#delete_bot_version)
    - [delete_intent](#delete_intent)
    - [delete_intent_version](#delete_intent_version)
    - [delete_slot_type](#delete_slot_type)
    - [delete_slot_type_version](#delete_slot_type_version)
    - [delete_utterances](#delete_utterances)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_bot](#get_bot)
    - [get_bot_alias](#get_bot_alias)
    - [get_bot_aliases](#get_bot_aliases)
    - [get_bot_channel_association](#get_bot_channel_association)
    - [get_bot_channel_associations](#get_bot_channel_associations)
    - [get_bot_versions](#get_bot_versions)
    - [get_bots](#get_bots)
    - [get_builtin_intent](#get_builtin_intent)
    - [get_builtin_intents](#get_builtin_intents)
    - [get_builtin_slot_types](#get_builtin_slot_types)
    - [get_export](#get_export)
    - [get_import](#get_import)
    - [get_intent](#get_intent)
    - [get_intent_versions](#get_intent_versions)
    - [get_intents](#get_intents)
    - [get_migration](#get_migration)
    - [get_migrations](#get_migrations)
    - [get_slot_type](#get_slot_type)
    - [get_slot_type_versions](#get_slot_type_versions)
    - [get_slot_types](#get_slot_types)
    - [get_utterances_view](#get_utterances_view)
    - [list_tags_for_resource](#list_tags_for_resource)
    - [put_bot](#put_bot)
    - [put_bot_alias](#put_bot_alias)
    - [put_intent](#put_intent)
    - [put_slot_type](#put_slot_type)
    - [start_import](#start_import)
    - [start_migration](#start_migration)
    - [tag_resource](#tag_resource)
    - [untag_resource](#untag_resource)
    - [__aenter__](#__aenter__)
    - [__aexit__](#__aexit__)
    - [get_paginator](#get_paginator)

<a id="lexmodelbuildingserviceclient"></a>

## LexModelBuildingServiceClient

Type annotations for `session.create_client("lex-models")`

Can be used directly:

```python
from aiobotocore.session import get_session
from types_aiobotocore_lex_models.client import LexModelBuildingServiceClient

session = get_session()
async with session.create_client("lex-models") as client:
    client: LexModelBuildingServiceClient
```

Boto3 documentation:
[LexModelBuildingService.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_lex_models.client import Exceptions

def handle_error(exc: Exceptions.AccessDeniedException) -> None:
    ...
```

Exceptions:

- `Exceptions.AccessDeniedException`
- `Exceptions.BadRequestException`
- `Exceptions.ClientError`
- `Exceptions.ConflictException`
- `Exceptions.InternalFailureException`
- `Exceptions.LimitExceededException`
- `Exceptions.NotFoundException`
- `Exceptions.PreconditionFailedException`
- `Exceptions.ResourceInUseException`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

LexModelBuildingServiceClient exceptions.

Type annotations for `session.create_client("lex-models").exceptions` method.

Boto3 documentation:
[LexModelBuildingService.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `session.create_client("lex-models").can_paginate` method.

Boto3 documentation:
[LexModelBuildingService.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.can_paginate)

Arguments:

- `operation_name`: `str` *(required)*

Returns `bool`.

<a id="create_bot_version"></a>

### create_bot_version

Creates a new version of the bot based on the `$LATEST` version.

Type annotations for `session.create_client("lex-models").create_bot_version`
method.

Boto3 documentation:
[LexModelBuildingService.Client.create_bot_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.create_bot_version)

Asynchronous method. Use `await create_bot_version(...)` for a synchronous
call.

Arguments mapping described in
[CreateBotVersionRequestRequestTypeDef](./type_defs.md#createbotversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `checksum`: `str`

Returns a `Coroutine` for
[CreateBotVersionResponseTypeDef](./type_defs.md#createbotversionresponsetypedef).

<a id="create_intent_version"></a>

### create_intent_version

Creates a new version of an intent based on the `$LATEST` version of the
intent.

Type annotations for
`session.create_client("lex-models").create_intent_version` method.

Boto3 documentation:
[LexModelBuildingService.Client.create_intent_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.create_intent_version)

Asynchronous method. Use `await create_intent_version(...)` for a synchronous
call.

Arguments mapping described in
[CreateIntentVersionRequestRequestTypeDef](./type_defs.md#createintentversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `checksum`: `str`

Returns a `Coroutine` for
[CreateIntentVersionResponseTypeDef](./type_defs.md#createintentversionresponsetypedef).

<a id="create_slot_type_version"></a>

### create_slot_type_version

Creates a new version of a slot type based on the `$LATEST` version of the
specified slot type.

Type annotations for
`session.create_client("lex-models").create_slot_type_version` method.

Boto3 documentation:
[LexModelBuildingService.Client.create_slot_type_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.create_slot_type_version)

Asynchronous method. Use `await create_slot_type_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateSlotTypeVersionRequestRequestTypeDef](./type_defs.md#createslottypeversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `checksum`: `str`

Returns a `Coroutine` for
[CreateSlotTypeVersionResponseTypeDef](./type_defs.md#createslottypeversionresponsetypedef).

<a id="delete_bot"></a>

### delete_bot

Deletes all versions of the bot, including the `$LATEST` version.

Type annotations for `session.create_client("lex-models").delete_bot` method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_bot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_bot)

Asynchronous method. Use `await delete_bot(...)` for a synchronous call.

Arguments mapping described in
[DeleteBotRequestRequestTypeDef](./type_defs.md#deletebotrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*

<a id="delete_bot_alias"></a>

### delete_bot_alias

Deletes an alias for the specified bot.

Type annotations for `session.create_client("lex-models").delete_bot_alias`
method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_bot_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_bot_alias)

Asynchronous method. Use `await delete_bot_alias(...)` for a synchronous call.

Arguments mapping described in
[DeleteBotAliasRequestRequestTypeDef](./type_defs.md#deletebotaliasrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `botName`: `str` *(required)*

<a id="delete_bot_channel_association"></a>

### delete_bot_channel_association

Deletes the association between an Amazon Lex bot and a messaging platform.

Type annotations for
`session.create_client("lex-models").delete_bot_channel_association` method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_bot_channel_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_bot_channel_association)

Asynchronous method. Use `await delete_bot_channel_association(...)` for a
synchronous call.

Arguments mapping described in
[DeleteBotChannelAssociationRequestRequestTypeDef](./type_defs.md#deletebotchannelassociationrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*

<a id="delete_bot_version"></a>

### delete_bot_version

Deletes a specific version of a bot.

Type annotations for `session.create_client("lex-models").delete_bot_version`
method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_bot_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_bot_version)

Asynchronous method. Use `await delete_bot_version(...)` for a synchronous
call.

Arguments mapping described in
[DeleteBotVersionRequestRequestTypeDef](./type_defs.md#deletebotversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*

<a id="delete_intent"></a>

### delete_intent

Deletes all versions of the intent, including the `$LATEST` version.

Type annotations for `session.create_client("lex-models").delete_intent`
method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_intent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_intent)

Asynchronous method. Use `await delete_intent(...)` for a synchronous call.

Arguments mapping described in
[DeleteIntentRequestRequestTypeDef](./type_defs.md#deleteintentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*

<a id="delete_intent_version"></a>

### delete_intent_version

Deletes a specific version of an intent.

Type annotations for
`session.create_client("lex-models").delete_intent_version` method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_intent_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_intent_version)

Asynchronous method. Use `await delete_intent_version(...)` for a synchronous
call.

Arguments mapping described in
[DeleteIntentVersionRequestRequestTypeDef](./type_defs.md#deleteintentversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*

<a id="delete_slot_type"></a>

### delete_slot_type

Deletes all versions of the slot type, including the `$LATEST` version.

Type annotations for `session.create_client("lex-models").delete_slot_type`
method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_slot_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_slot_type)

Asynchronous method. Use `await delete_slot_type(...)` for a synchronous call.

Arguments mapping described in
[DeleteSlotTypeRequestRequestTypeDef](./type_defs.md#deleteslottyperequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*

<a id="delete_slot_type_version"></a>

### delete_slot_type_version

Deletes a specific version of a slot type.

Type annotations for
`session.create_client("lex-models").delete_slot_type_version` method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_slot_type_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_slot_type_version)

Asynchronous method. Use `await delete_slot_type_version(...)` for a
synchronous call.

Arguments mapping described in
[DeleteSlotTypeVersionRequestRequestTypeDef](./type_defs.md#deleteslottypeversionrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*

<a id="delete_utterances"></a>

### delete_utterances

Deletes stored utterances.

Type annotations for `session.create_client("lex-models").delete_utterances`
method.

Boto3 documentation:
[LexModelBuildingService.Client.delete_utterances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.delete_utterances)

Asynchronous method. Use `await delete_utterances(...)` for a synchronous call.

Arguments mapping described in
[DeleteUtterancesRequestRequestTypeDef](./type_defs.md#deleteutterancesrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `userId`: `str` *(required)*

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for
`session.create_client("lex-models").generate_presigned_url` method.

Boto3 documentation:
[LexModelBuildingService.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_bot"></a>

### get_bot

Returns metadata information for a specific bot.

Type annotations for `session.create_client("lex-models").get_bot` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot)

Asynchronous method. Use `await get_bot(...)` for a synchronous call.

Arguments mapping described in
[GetBotRequestRequestTypeDef](./type_defs.md#getbotrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `versionOrAlias`: `str` *(required)*

Returns a `Coroutine` for
[GetBotResponseTypeDef](./type_defs.md#getbotresponsetypedef).

<a id="get_bot_alias"></a>

### get_bot_alias

Returns information about an Amazon Lex bot alias.

Type annotations for `session.create_client("lex-models").get_bot_alias`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_alias)

Asynchronous method. Use `await get_bot_alias(...)` for a synchronous call.

Arguments mapping described in
[GetBotAliasRequestRequestTypeDef](./type_defs.md#getbotaliasrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `botName`: `str` *(required)*

Returns a `Coroutine` for
[GetBotAliasResponseTypeDef](./type_defs.md#getbotaliasresponsetypedef).

<a id="get_bot_aliases"></a>

### get_bot_aliases

Returns a list of aliases for a specified Amazon Lex bot.

Type annotations for `session.create_client("lex-models").get_bot_aliases`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot_aliases](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_aliases)

Asynchronous method. Use `await get_bot_aliases(...)` for a synchronous call.

Arguments mapping described in
[GetBotAliasesRequestRequestTypeDef](./type_defs.md#getbotaliasesrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `nameContains`: `str`

Returns a `Coroutine` for
[GetBotAliasesResponseTypeDef](./type_defs.md#getbotaliasesresponsetypedef).

<a id="get_bot_channel_association"></a>

### get_bot_channel_association

Returns information about the association between an Amazon Lex bot and a
messaging platform.

Type annotations for
`session.create_client("lex-models").get_bot_channel_association` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot_channel_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_channel_association)

Asynchronous method. Use `await get_bot_channel_association(...)` for a
synchronous call.

Arguments mapping described in
[GetBotChannelAssociationRequestRequestTypeDef](./type_defs.md#getbotchannelassociationrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*

Returns a `Coroutine` for
[GetBotChannelAssociationResponseTypeDef](./type_defs.md#getbotchannelassociationresponsetypedef).

<a id="get_bot_channel_associations"></a>

### get_bot_channel_associations

Returns a list of all of the channels associated with the specified bot.

Type annotations for
`session.create_client("lex-models").get_bot_channel_associations` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot_channel_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_channel_associations)

Asynchronous method. Use `await get_bot_channel_associations(...)` for a
synchronous call.

Arguments mapping described in
[GetBotChannelAssociationsRequestRequestTypeDef](./type_defs.md#getbotchannelassociationsrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botAlias`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`
- `nameContains`: `str`

Returns a `Coroutine` for
[GetBotChannelAssociationsResponseTypeDef](./type_defs.md#getbotchannelassociationsresponsetypedef).

<a id="get_bot_versions"></a>

### get_bot_versions

Gets information about all of the versions of a bot.

Type annotations for `session.create_client("lex-models").get_bot_versions`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bot_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_versions)

Asynchronous method. Use `await get_bot_versions(...)` for a synchronous call.

Arguments mapping described in
[GetBotVersionsRequestRequestTypeDef](./type_defs.md#getbotversionsrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetBotVersionsResponseTypeDef](./type_defs.md#getbotversionsresponsetypedef).

<a id="get_bots"></a>

### get_bots

Returns bot information as follows * If you provide the `nameContains` field,
the response includes information for the `$LATEST` version of all bots whose
name contains the specified string.

Type annotations for `session.create_client("lex-models").get_bots` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_bots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bots)

Asynchronous method. Use `await get_bots(...)` for a synchronous call.

Arguments mapping described in
[GetBotsRequestRequestTypeDef](./type_defs.md#getbotsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `nameContains`: `str`

Returns a `Coroutine` for
[GetBotsResponseTypeDef](./type_defs.md#getbotsresponsetypedef).

<a id="get_builtin_intent"></a>

### get_builtin_intent

Returns information about a built-in intent.

Type annotations for `session.create_client("lex-models").get_builtin_intent`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_builtin_intent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_builtin_intent)

Asynchronous method. Use `await get_builtin_intent(...)` for a synchronous
call.

Arguments mapping described in
[GetBuiltinIntentRequestRequestTypeDef](./type_defs.md#getbuiltinintentrequestrequesttypedef).

Keyword-only arguments:

- `signature`: `str` *(required)*

Returns a `Coroutine` for
[GetBuiltinIntentResponseTypeDef](./type_defs.md#getbuiltinintentresponsetypedef).

<a id="get_builtin_intents"></a>

### get_builtin_intents

Gets a list of built-in intents that meet the specified criteria.

Type annotations for `session.create_client("lex-models").get_builtin_intents`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_builtin_intents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_builtin_intents)

Asynchronous method. Use `await get_builtin_intents(...)` for a synchronous
call.

Arguments mapping described in
[GetBuiltinIntentsRequestRequestTypeDef](./type_defs.md#getbuiltinintentsrequestrequesttypedef).

Keyword-only arguments:

- `locale`: [LocaleType](./literals.md#localetype)
- `signatureContains`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetBuiltinIntentsResponseTypeDef](./type_defs.md#getbuiltinintentsresponsetypedef).

<a id="get_builtin_slot_types"></a>

### get_builtin_slot_types

Gets a list of built-in slot types that meet the specified criteria.

Type annotations for
`session.create_client("lex-models").get_builtin_slot_types` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_builtin_slot_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_builtin_slot_types)

Asynchronous method. Use `await get_builtin_slot_types(...)` for a synchronous
call.

Arguments mapping described in
[GetBuiltinSlotTypesRequestRequestTypeDef](./type_defs.md#getbuiltinslottypesrequestrequesttypedef).

Keyword-only arguments:

- `locale`: [LocaleType](./literals.md#localetype)
- `signatureContains`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetBuiltinSlotTypesResponseTypeDef](./type_defs.md#getbuiltinslottypesresponsetypedef).

<a id="get_export"></a>

### get_export

Exports the contents of a Amazon Lex resource in a specified format.

Type annotations for `session.create_client("lex-models").get_export` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_export](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_export)

Asynchronous method. Use `await get_export(...)` for a synchronous call.

Arguments mapping described in
[GetExportRequestRequestTypeDef](./type_defs.md#getexportrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*
- `resourceType`: [ResourceTypeType](./literals.md#resourcetypetype)
  *(required)*
- `exportType`: [ExportTypeType](./literals.md#exporttypetype) *(required)*

Returns a `Coroutine` for
[GetExportResponseTypeDef](./type_defs.md#getexportresponsetypedef).

<a id="get_import"></a>

### get_import

Gets information about an import job started with the `StartImport` operation.

Type annotations for `session.create_client("lex-models").get_import` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_import](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_import)

Asynchronous method. Use `await get_import(...)` for a synchronous call.

Arguments mapping described in
[GetImportRequestRequestTypeDef](./type_defs.md#getimportrequestrequesttypedef).

Keyword-only arguments:

- `importId`: `str` *(required)*

Returns a `Coroutine` for
[GetImportResponseTypeDef](./type_defs.md#getimportresponsetypedef).

<a id="get_intent"></a>

### get_intent

Returns information about an intent.

Type annotations for `session.create_client("lex-models").get_intent` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_intent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intent)

Asynchronous method. Use `await get_intent(...)` for a synchronous call.

Arguments mapping described in
[GetIntentRequestRequestTypeDef](./type_defs.md#getintentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*

Returns a `Coroutine` for
[GetIntentResponseTypeDef](./type_defs.md#getintentresponsetypedef).

<a id="get_intent_versions"></a>

### get_intent_versions

Gets information about all of the versions of an intent.

Type annotations for `session.create_client("lex-models").get_intent_versions`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_intent_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intent_versions)

Asynchronous method. Use `await get_intent_versions(...)` for a synchronous
call.

Arguments mapping described in
[GetIntentVersionsRequestRequestTypeDef](./type_defs.md#getintentversionsrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetIntentVersionsResponseTypeDef](./type_defs.md#getintentversionsresponsetypedef).

<a id="get_intents"></a>

### get_intents

Returns intent information as follows * If you specify the `nameContains`
field, returns the `$LATEST` version of all intents that contain the specified
string.

Type annotations for `session.create_client("lex-models").get_intents` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_intents](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intents)

Asynchronous method. Use `await get_intents(...)` for a synchronous call.

Arguments mapping described in
[GetIntentsRequestRequestTypeDef](./type_defs.md#getintentsrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `nameContains`: `str`

Returns a `Coroutine` for
[GetIntentsResponseTypeDef](./type_defs.md#getintentsresponsetypedef).

<a id="get_migration"></a>

### get_migration

Provides details about an ongoing or complete migration from an Amazon Lex V1
bot to an Amazon Lex V2 bot.

Type annotations for `session.create_client("lex-models").get_migration`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_migration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_migration)

Asynchronous method. Use `await get_migration(...)` for a synchronous call.

Arguments mapping described in
[GetMigrationRequestRequestTypeDef](./type_defs.md#getmigrationrequestrequesttypedef).

Keyword-only arguments:

- `migrationId`: `str` *(required)*

Returns a `Coroutine` for
[GetMigrationResponseTypeDef](./type_defs.md#getmigrationresponsetypedef).

<a id="get_migrations"></a>

### get_migrations

Gets a list of migrations between Amazon Lex V1 and Amazon Lex V2.

Type annotations for `session.create_client("lex-models").get_migrations`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_migrations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_migrations)

Asynchronous method. Use `await get_migrations(...)` for a synchronous call.

Arguments mapping described in
[GetMigrationsRequestRequestTypeDef](./type_defs.md#getmigrationsrequestrequesttypedef).

Keyword-only arguments:

- `sortByAttribute`:
  [MigrationSortAttributeType](./literals.md#migrationsortattributetype)
- `sortByOrder`: [SortOrderType](./literals.md#sortordertype)
- `v1BotNameContains`: `str`
- `migrationStatusEquals`:
  [MigrationStatusType](./literals.md#migrationstatustype)
- `maxResults`: `int`
- `nextToken`: `str`

Returns a `Coroutine` for
[GetMigrationsResponseTypeDef](./type_defs.md#getmigrationsresponsetypedef).

<a id="get_slot_type"></a>

### get_slot_type

Returns information about a specific version of a slot type.

Type annotations for `session.create_client("lex-models").get_slot_type`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_slot_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_type)

Asynchronous method. Use `await get_slot_type(...)` for a synchronous call.

Arguments mapping described in
[GetSlotTypeRequestRequestTypeDef](./type_defs.md#getslottyperequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `version`: `str` *(required)*

Returns a `Coroutine` for
[GetSlotTypeResponseTypeDef](./type_defs.md#getslottyperesponsetypedef).

<a id="get_slot_type_versions"></a>

### get_slot_type_versions

Gets information about all versions of a slot type.

Type annotations for
`session.create_client("lex-models").get_slot_type_versions` method.

Boto3 documentation:
[LexModelBuildingService.Client.get_slot_type_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_type_versions)

Asynchronous method. Use `await get_slot_type_versions(...)` for a synchronous
call.

Arguments mapping described in
[GetSlotTypeVersionsRequestRequestTypeDef](./type_defs.md#getslottypeversionsrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `nextToken`: `str`
- `maxResults`: `int`

Returns a `Coroutine` for
[GetSlotTypeVersionsResponseTypeDef](./type_defs.md#getslottypeversionsresponsetypedef).

<a id="get_slot_types"></a>

### get_slot_types

Returns slot type information as follows * If you specify the `nameContains`
field, returns the `$LATEST` version of all slot types that contain the
specified string.

Type annotations for `session.create_client("lex-models").get_slot_types`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_slot_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_types)

Asynchronous method. Use `await get_slot_types(...)` for a synchronous call.

Arguments mapping described in
[GetSlotTypesRequestRequestTypeDef](./type_defs.md#getslottypesrequestrequesttypedef).

Keyword-only arguments:

- `nextToken`: `str`
- `maxResults`: `int`
- `nameContains`: `str`

Returns a `Coroutine` for
[GetSlotTypesResponseTypeDef](./type_defs.md#getslottypesresponsetypedef).

<a id="get_utterances_view"></a>

### get_utterances_view

Use the `GetUtterancesView` operation to get information about the utterances
that your users have made to your bot.

Type annotations for `session.create_client("lex-models").get_utterances_view`
method.

Boto3 documentation:
[LexModelBuildingService.Client.get_utterances_view](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_utterances_view)

Asynchronous method. Use `await get_utterances_view(...)` for a synchronous
call.

Arguments mapping described in
[GetUtterancesViewRequestRequestTypeDef](./type_defs.md#getutterancesviewrequestrequesttypedef).

Keyword-only arguments:

- `botName`: `str` *(required)*
- `botVersions`: `Sequence`\[`str`\] *(required)*
- `statusType`: [StatusTypeType](./literals.md#statustypetype) *(required)*

Returns a `Coroutine` for
[GetUtterancesViewResponseTypeDef](./type_defs.md#getutterancesviewresponsetypedef).

<a id="list_tags_for_resource"></a>

### list_tags_for_resource

Gets a list of tags associated with the specified resource.

Type annotations for
`session.create_client("lex-models").list_tags_for_resource` method.

Boto3 documentation:
[LexModelBuildingService.Client.list_tags_for_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.list_tags_for_resource)

Asynchronous method. Use `await list_tags_for_resource(...)` for a synchronous
call.

Arguments mapping described in
[ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*

Returns a `Coroutine` for
[ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef).

<a id="put_bot"></a>

### put_bot

Creates an Amazon Lex conversational bot or replaces an existing bot.

Type annotations for `session.create_client("lex-models").put_bot` method.

Boto3 documentation:
[LexModelBuildingService.Client.put_bot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.put_bot)

Asynchronous method. Use `await put_bot(...)` for a synchronous call.

Arguments mapping described in
[PutBotRequestRequestTypeDef](./type_defs.md#putbotrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `locale`: [LocaleType](./literals.md#localetype) *(required)*
- `childDirected`: `bool` *(required)*
- `description`: `str`
- `intents`: `Sequence`\[[IntentTypeDef](./type_defs.md#intenttypedef)\]
- `enableModelImprovements`: `bool`
- `nluIntentConfidenceThreshold`: `float`
- `clarificationPrompt`: [PromptTypeDef](./type_defs.md#prompttypedef)
- `abortStatement`: [StatementTypeDef](./type_defs.md#statementtypedef)
- `idleSessionTTLInSeconds`: `int`
- `voiceId`: `str`
- `checksum`: `str`
- `processBehavior`: [ProcessBehaviorType](./literals.md#processbehaviortype)
- `detectSentiment`: `bool`
- `createVersion`: `bool`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PutBotResponseTypeDef](./type_defs.md#putbotresponsetypedef).

<a id="put_bot_alias"></a>

### put_bot_alias

Creates an alias for the specified version of the bot or replaces an alias for
the specified bot.

Type annotations for `session.create_client("lex-models").put_bot_alias`
method.

Boto3 documentation:
[LexModelBuildingService.Client.put_bot_alias](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.put_bot_alias)

Asynchronous method. Use `await put_bot_alias(...)` for a synchronous call.

Arguments mapping described in
[PutBotAliasRequestRequestTypeDef](./type_defs.md#putbotaliasrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `botVersion`: `str` *(required)*
- `botName`: `str` *(required)*
- `description`: `str`
- `checksum`: `str`
- `conversationLogs`:
  [ConversationLogsRequestTypeDef](./type_defs.md#conversationlogsrequesttypedef)
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[PutBotAliasResponseTypeDef](./type_defs.md#putbotaliasresponsetypedef).

<a id="put_intent"></a>

### put_intent

Creates an intent or replaces an existing intent.

Type annotations for `session.create_client("lex-models").put_intent` method.

Boto3 documentation:
[LexModelBuildingService.Client.put_intent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.put_intent)

Asynchronous method. Use `await put_intent(...)` for a synchronous call.

Arguments mapping described in
[PutIntentRequestRequestTypeDef](./type_defs.md#putintentrequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `description`: `str`
- `slots`: `Sequence`\[[SlotTypeDef](./type_defs.md#slottypedef)\]
- `sampleUtterances`: `Sequence`\[`str`\]
- `confirmationPrompt`: [PromptTypeDef](./type_defs.md#prompttypedef)
- `rejectionStatement`: [StatementTypeDef](./type_defs.md#statementtypedef)
- `followUpPrompt`:
  [FollowUpPromptTypeDef](./type_defs.md#followupprompttypedef)
- `conclusionStatement`: [StatementTypeDef](./type_defs.md#statementtypedef)
- `dialogCodeHook`: [CodeHookTypeDef](./type_defs.md#codehooktypedef)
- `fulfillmentActivity`:
  [FulfillmentActivityTypeDef](./type_defs.md#fulfillmentactivitytypedef)
- `parentIntentSignature`: `str`
- `checksum`: `str`
- `createVersion`: `bool`
- `kendraConfiguration`:
  [KendraConfigurationTypeDef](./type_defs.md#kendraconfigurationtypedef)
- `inputContexts`:
  `Sequence`\[[InputContextTypeDef](./type_defs.md#inputcontexttypedef)\]
- `outputContexts`:
  `Sequence`\[[OutputContextTypeDef](./type_defs.md#outputcontexttypedef)\]

Returns a `Coroutine` for
[PutIntentResponseTypeDef](./type_defs.md#putintentresponsetypedef).

<a id="put_slot_type"></a>

### put_slot_type

Creates a custom slot type or replaces an existing custom slot type.

Type annotations for `session.create_client("lex-models").put_slot_type`
method.

Boto3 documentation:
[LexModelBuildingService.Client.put_slot_type](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.put_slot_type)

Asynchronous method. Use `await put_slot_type(...)` for a synchronous call.

Arguments mapping described in
[PutSlotTypeRequestRequestTypeDef](./type_defs.md#putslottyperequestrequesttypedef).

Keyword-only arguments:

- `name`: `str` *(required)*
- `description`: `str`
- `enumerationValues`:
  `Sequence`\[[EnumerationValueTypeDef](./type_defs.md#enumerationvaluetypedef)\]
- `checksum`: `str`
- `valueSelectionStrategy`:
  [SlotValueSelectionStrategyType](./literals.md#slotvalueselectionstrategytype)
- `createVersion`: `bool`
- `parentSlotTypeSignature`: `str`
- `slotTypeConfigurations`:
  `Sequence`\[[SlotTypeConfigurationTypeDef](./type_defs.md#slottypeconfigurationtypedef)\]

Returns a `Coroutine` for
[PutSlotTypeResponseTypeDef](./type_defs.md#putslottyperesponsetypedef).

<a id="start_import"></a>

### start_import

Starts a job to import a resource to Amazon Lex.

Type annotations for `session.create_client("lex-models").start_import` method.

Boto3 documentation:
[LexModelBuildingService.Client.start_import](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.start_import)

Asynchronous method. Use `await start_import(...)` for a synchronous call.

Arguments mapping described in
[StartImportRequestRequestTypeDef](./type_defs.md#startimportrequestrequesttypedef).

Keyword-only arguments:

- `payload`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\] *(required)*
- `resourceType`: [ResourceTypeType](./literals.md#resourcetypetype)
  *(required)*
- `mergeStrategy`: [MergeStrategyType](./literals.md#mergestrategytype)
  *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

Returns a `Coroutine` for
[StartImportResponseTypeDef](./type_defs.md#startimportresponsetypedef).

<a id="start_migration"></a>

### start_migration

Starts migrating a bot from Amazon Lex V1 to Amazon Lex V2.

Type annotations for `session.create_client("lex-models").start_migration`
method.

Boto3 documentation:
[LexModelBuildingService.Client.start_migration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.start_migration)

Asynchronous method. Use `await start_migration(...)` for a synchronous call.

Arguments mapping described in
[StartMigrationRequestRequestTypeDef](./type_defs.md#startmigrationrequestrequesttypedef).

Keyword-only arguments:

- `v1BotName`: `str` *(required)*
- `v1BotVersion`: `str` *(required)*
- `v2BotName`: `str` *(required)*
- `v2BotRole`: `str` *(required)*
- `migrationStrategy`:
  [MigrationStrategyType](./literals.md#migrationstrategytype) *(required)*

Returns a `Coroutine` for
[StartMigrationResponseTypeDef](./type_defs.md#startmigrationresponsetypedef).

<a id="tag_resource"></a>

### tag_resource

Adds the specified tags to the specified resource.

Type annotations for `session.create_client("lex-models").tag_resource` method.

Boto3 documentation:
[LexModelBuildingService.Client.tag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.tag_resource)

Asynchronous method. Use `await tag_resource(...)` for a synchronous call.

Arguments mapping described in
[TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="untag_resource"></a>

### untag_resource

Removes tags from a bot, bot alias or bot channel.

Type annotations for `session.create_client("lex-models").untag_resource`
method.

Boto3 documentation:
[LexModelBuildingService.Client.untag_resource](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.untag_resource)

Asynchronous method. Use `await untag_resource(...)` for a synchronous call.

Arguments mapping described in
[UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef).

Keyword-only arguments:

- `resourceArn`: `str` *(required)*
- `tagKeys`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for `Dict`\[`str`, `Any`\].

<a id="__aenter__"></a>

### __aenter__

Type annotations for `session.create_client("lex-models").__aenter__` method.

Boto3 documentation:
[LexModelBuildingService.Client.__aenter__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.__aenter__)

Asynchronous method. Use `await __aenter__(...)` for a synchronous call.

Returns a `Coroutine` for
[LexModelBuildingServiceClient](#lexmodelbuildingserviceclient).

<a id="__aexit__"></a>

### __aexit__

Type annotations for `session.create_client("lex-models").__aexit__` method.

Boto3 documentation:
[LexModelBuildingService.Client.__aexit__](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.__aexit__)

Asynchronous method. Use `await __aexit__(...)` for a synchronous call.

Arguments:

- `exc_type`: `Any` *(required)*
- `exc_val`: `Any` *(required)*
- `exc_tb`: `Any` *(required)*

Returns a `Coroutine` for `Any`.

<a id="get_paginator"></a>

### get_paginator

Type annotations for `session.create_client("lex-models").get_paginator` method
with overloads.

- `client.get_paginator("get_bot_aliases")` ->
  [GetBotAliasesPaginator](./paginators.md#getbotaliasespaginator)
- `client.get_paginator("get_bot_channel_associations")` ->
  [GetBotChannelAssociationsPaginator](./paginators.md#getbotchannelassociationspaginator)
- `client.get_paginator("get_bot_versions")` ->
  [GetBotVersionsPaginator](./paginators.md#getbotversionspaginator)
- `client.get_paginator("get_bots")` ->
  [GetBotsPaginator](./paginators.md#getbotspaginator)
- `client.get_paginator("get_builtin_intents")` ->
  [GetBuiltinIntentsPaginator](./paginators.md#getbuiltinintentspaginator)
- `client.get_paginator("get_builtin_slot_types")` ->
  [GetBuiltinSlotTypesPaginator](./paginators.md#getbuiltinslottypespaginator)
- `client.get_paginator("get_intent_versions")` ->
  [GetIntentVersionsPaginator](./paginators.md#getintentversionspaginator)
- `client.get_paginator("get_intents")` ->
  [GetIntentsPaginator](./paginators.md#getintentspaginator)
- `client.get_paginator("get_slot_type_versions")` ->
  [GetSlotTypeVersionsPaginator](./paginators.md#getslottypeversionspaginator)
- `client.get_paginator("get_slot_types")` ->
  [GetSlotTypesPaginator](./paginators.md#getslottypespaginator)
