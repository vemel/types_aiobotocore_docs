<a id="typed-dictionaries-for-aiobotocore-lexruntimev2-module"></a>

# Typed dictionaries for aiobotocore LexRuntimeV2 module

> [Index](..) > [LexRuntimeV2](.) > Typed dictionaries

Auto-generated documentation for
[LexRuntimeV2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-runtime.html#LexRuntimeV2)
type annotations stubs module
[types-aiobotocore-lexv2-runtime](https://pypi.org/project/types-aiobotocore-lexv2-runtime/).

- [Typed dictionaries for aiobotocore LexRuntimeV2 module](#typed-dictionaries-for-aiobotocore-lexruntimev2-module)
  - [ActiveContextTimeToLiveTypeDef](#activecontexttimetolivetypedef)
  - [ActiveContextTypeDef](#activecontexttypedef)
  - [ButtonTypeDef](#buttontypedef)
  - [ConfidenceScoreTypeDef](#confidencescoretypedef)
  - [DeleteSessionRequestRequestTypeDef](#deletesessionrequestrequesttypedef)
  - [DeleteSessionResponseTypeDef](#deletesessionresponsetypedef)
  - [DialogActionTypeDef](#dialogactiontypedef)
  - [GetSessionRequestRequestTypeDef](#getsessionrequestrequesttypedef)
  - [GetSessionResponseTypeDef](#getsessionresponsetypedef)
  - [ImageResponseCardTypeDef](#imageresponsecardtypedef)
  - [IntentTypeDef](#intenttypedef)
  - [InterpretationTypeDef](#interpretationtypedef)
  - [MessageTypeDef](#messagetypedef)
  - [PutSessionRequestRequestTypeDef](#putsessionrequestrequesttypedef)
  - [PutSessionResponseTypeDef](#putsessionresponsetypedef)
  - [RecognizeTextRequestRequestTypeDef](#recognizetextrequestrequesttypedef)
  - [RecognizeTextResponseTypeDef](#recognizetextresponsetypedef)
  - [RecognizeUtteranceRequestRequestTypeDef](#recognizeutterancerequestrequesttypedef)
  - [RecognizeUtteranceResponseTypeDef](#recognizeutteranceresponsetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [SentimentResponseTypeDef](#sentimentresponsetypedef)
  - [SentimentScoreTypeDef](#sentimentscoretypedef)
  - [SessionStateTypeDef](#sessionstatetypedef)
  - [SlotTypeDef](#slottypedef)
  - [ValueTypeDef](#valuetypedef)

<a id="activecontexttimetolivetypedef"></a>

## ActiveContextTimeToLiveTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ActiveContextTimeToLiveTypeDef
```

Required fields:

- `timeToLiveInSeconds`: `int`
- `turnsToLive`: `int`

<a id="activecontexttypedef"></a>

## ActiveContextTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ActiveContextTypeDef
```

Required fields:

- `name`: `str`
- `timeToLive`:
  [ActiveContextTimeToLiveTypeDef](./type_defs.md#activecontexttimetolivetypedef)
- `contextAttributes`: `Dict`\[`str`, `str`\]

<a id="buttontypedef"></a>

## ButtonTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ButtonTypeDef
```

Required fields:

- `text`: `str`
- `value`: `str`

<a id="confidencescoretypedef"></a>

## ConfidenceScoreTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ConfidenceScoreTypeDef
```

Optional fields:

- `score`: `float`

<a id="deletesessionrequestrequesttypedef"></a>

## DeleteSessionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import DeleteSessionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`

<a id="deletesessionresponsetypedef"></a>

## DeleteSessionResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import DeleteSessionResponseTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="dialogactiontypedef"></a>

## DialogActionTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import DialogActionTypeDef
```

Required fields:

- `type`: [DialogActionTypeType](./literals.md#dialogactiontypetype)

Optional fields:

- `slotToElicit`: `str`
- `slotElicitationStyle`: [StyleTypeType](./literals.md#styletypetype)

<a id="getsessionrequestrequesttypedef"></a>

## GetSessionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import GetSessionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`

<a id="getsessionresponsetypedef"></a>

## GetSessionResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import GetSessionResponseTypeDef
```

Required fields:

- `sessionId`: `str`
- `messages`: `List`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]
- `interpretations`:
  `List`\[[InterpretationTypeDef](./type_defs.md#interpretationtypedef)\]
- `sessionState`: [SessionStateTypeDef](./type_defs.md#sessionstatetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="imageresponsecardtypedef"></a>

## ImageResponseCardTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ImageResponseCardTypeDef
```

Required fields:

- `title`: `str`

Optional fields:

- `subtitle`: `str`
- `imageUrl`: `str`
- `buttons`: `List`\[[ButtonTypeDef](./type_defs.md#buttontypedef)\]

<a id="intenttypedef"></a>

## IntentTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import IntentTypeDef
```

Required fields:

- `name`: `str`

Optional fields:

- `slots`: `Dict`\[`str`, [SlotTypeDef](./type_defs.md#slottypedef)\]
- `state`: [IntentStateType](./literals.md#intentstatetype)
- `confirmationState`:
  [ConfirmationStateType](./literals.md#confirmationstatetype)

<a id="interpretationtypedef"></a>

## InterpretationTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import InterpretationTypeDef
```

Optional fields:

- `nluConfidence`:
  [ConfidenceScoreTypeDef](./type_defs.md#confidencescoretypedef)
- `sentimentResponse`:
  [SentimentResponseTypeDef](./type_defs.md#sentimentresponsetypedef)
- `intent`: [IntentTypeDef](./type_defs.md#intenttypedef)

<a id="messagetypedef"></a>

## MessageTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import MessageTypeDef
```

Required fields:

- `contentType`: [MessageContentTypeType](./literals.md#messagecontenttypetype)

Optional fields:

- `content`: `str`
- `imageResponseCard`:
  [ImageResponseCardTypeDef](./type_defs.md#imageresponsecardtypedef)

<a id="putsessionrequestrequesttypedef"></a>

## PutSessionRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import PutSessionRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`
- `sessionState`: [SessionStateTypeDef](./type_defs.md#sessionstatetypedef)

Optional fields:

- `messages`: `Sequence`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]
- `requestAttributes`: `Mapping`\[`str`, `str`\]
- `responseContentType`: `str`

<a id="putsessionresponsetypedef"></a>

## PutSessionResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import PutSessionResponseTypeDef
```

Required fields:

- `contentType`: `str`
- `messages`: `str`
- `sessionState`: `str`
- `requestAttributes`: `str`
- `sessionId`: `str`
- `audioStream`: `StreamingBody`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="recognizetextrequestrequesttypedef"></a>

## RecognizeTextRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import RecognizeTextRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`
- `text`: `str`

Optional fields:

- `sessionState`: [SessionStateTypeDef](./type_defs.md#sessionstatetypedef)
- `requestAttributes`: `Mapping`\[`str`, `str`\]

<a id="recognizetextresponsetypedef"></a>

## RecognizeTextResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import RecognizeTextResponseTypeDef
```

Required fields:

- `messages`: `List`\[[MessageTypeDef](./type_defs.md#messagetypedef)\]
- `sessionState`: [SessionStateTypeDef](./type_defs.md#sessionstatetypedef)
- `interpretations`:
  `List`\[[InterpretationTypeDef](./type_defs.md#interpretationtypedef)\]
- `requestAttributes`: `Dict`\[`str`, `str`\]
- `sessionId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="recognizeutterancerequestrequesttypedef"></a>

## RecognizeUtteranceRequestRequestTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import RecognizeUtteranceRequestRequestTypeDef
```

Required fields:

- `botId`: `str`
- `botAliasId`: `str`
- `localeId`: `str`
- `sessionId`: `str`
- `requestContentType`: `str`

Optional fields:

- `sessionState`: `str`
- `requestAttributes`: `str`
- `responseContentType`: `str`
- `inputStream`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]

<a id="recognizeutteranceresponsetypedef"></a>

## RecognizeUtteranceResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import RecognizeUtteranceResponseTypeDef
```

Required fields:

- `inputMode`: `str`
- `contentType`: `str`
- `messages`: `str`
- `interpretations`: `str`
- `sessionState`: `str`
- `requestAttributes`: `str`
- `sessionId`: `str`
- `inputTranscript`: `str`
- `audioStream`: `StreamingBody`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="sentimentresponsetypedef"></a>

## SentimentResponseTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import SentimentResponseTypeDef
```

Optional fields:

- `sentiment`: [SentimentTypeType](./literals.md#sentimenttypetype)
- `sentimentScore`:
  [SentimentScoreTypeDef](./type_defs.md#sentimentscoretypedef)

<a id="sentimentscoretypedef"></a>

## SentimentScoreTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import SentimentScoreTypeDef
```

Optional fields:

- `positive`: `float`
- `negative`: `float`
- `neutral`: `float`
- `mixed`: `float`

<a id="sessionstatetypedef"></a>

## SessionStateTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import SessionStateTypeDef
```

Optional fields:

- `dialogAction`: [DialogActionTypeDef](./type_defs.md#dialogactiontypedef)
- `intent`: [IntentTypeDef](./type_defs.md#intenttypedef)
- `activeContexts`:
  `List`\[[ActiveContextTypeDef](./type_defs.md#activecontexttypedef)\]
- `sessionAttributes`: `Dict`\[`str`, `str`\]
- `originatingRequestId`: `str`

<a id="slottypedef"></a>

## SlotTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import SlotTypeDef
```

Optional fields:

- `value`: [ValueTypeDef](./type_defs.md#valuetypedef)
- `shape`: [ShapeType](./literals.md#shapetype)
- `values`: `List`\[[SlotTypeDef](./type_defs.md#slottypedef)\]

<a id="valuetypedef"></a>

## ValueTypeDef

```python
from types_aiobotocore_lexv2_runtime.type_defs import ValueTypeDef
```

Required fields:

- `interpretedValue`: `str`

Optional fields:

- `originalValue`: `str`
- `resolvedValues`: `List`\[`str`\]
