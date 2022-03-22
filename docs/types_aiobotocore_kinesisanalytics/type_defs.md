<a id="typed-dictionaries-for-aiobotocore-kinesisanalytics-module"></a>

# Typed dictionaries for aiobotocore KinesisAnalytics module

> [Index](../README.md) > [KinesisAnalytics](./README.md) > Typed dictionaries

Auto-generated documentation for
[KinesisAnalytics](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kinesisanalytics.html#KinesisAnalytics)
type annotations stubs module
[types-aiobotocore-kinesisanalytics](https://pypi.org/project/types-aiobotocore-kinesisanalytics/).

- [Typed dictionaries for aiobotocore KinesisAnalytics module](#typed-dictionaries-for-aiobotocore-kinesisanalytics-module)
  - [AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef](#addapplicationcloudwatchloggingoptionrequestrequesttypedef)
  - [AddApplicationInputProcessingConfigurationRequestRequestTypeDef](#addapplicationinputprocessingconfigurationrequestrequesttypedef)
  - [AddApplicationInputRequestRequestTypeDef](#addapplicationinputrequestrequesttypedef)
  - [AddApplicationOutputRequestRequestTypeDef](#addapplicationoutputrequestrequesttypedef)
  - [AddApplicationReferenceDataSourceRequestRequestTypeDef](#addapplicationreferencedatasourcerequestrequesttypedef)
  - [ApplicationDetailTypeDef](#applicationdetailtypedef)
  - [ApplicationSummaryTypeDef](#applicationsummarytypedef)
  - [ApplicationUpdateTypeDef](#applicationupdatetypedef)
  - [CSVMappingParametersTypeDef](#csvmappingparameterstypedef)
  - [CloudWatchLoggingOptionDescriptionTypeDef](#cloudwatchloggingoptiondescriptiontypedef)
  - [CloudWatchLoggingOptionTypeDef](#cloudwatchloggingoptiontypedef)
  - [CloudWatchLoggingOptionUpdateTypeDef](#cloudwatchloggingoptionupdatetypedef)
  - [CreateApplicationRequestRequestTypeDef](#createapplicationrequestrequesttypedef)
  - [CreateApplicationResponseTypeDef](#createapplicationresponsetypedef)
  - [DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef](#deleteapplicationcloudwatchloggingoptionrequestrequesttypedef)
  - [DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef](#deleteapplicationinputprocessingconfigurationrequestrequesttypedef)
  - [DeleteApplicationOutputRequestRequestTypeDef](#deleteapplicationoutputrequestrequesttypedef)
  - [DeleteApplicationReferenceDataSourceRequestRequestTypeDef](#deleteapplicationreferencedatasourcerequestrequesttypedef)
  - [DeleteApplicationRequestRequestTypeDef](#deleteapplicationrequestrequesttypedef)
  - [DescribeApplicationRequestRequestTypeDef](#describeapplicationrequestrequesttypedef)
  - [DescribeApplicationResponseTypeDef](#describeapplicationresponsetypedef)
  - [DestinationSchemaTypeDef](#destinationschematypedef)
  - [DiscoverInputSchemaRequestRequestTypeDef](#discoverinputschemarequestrequesttypedef)
  - [DiscoverInputSchemaResponseTypeDef](#discoverinputschemaresponsetypedef)
  - [InputConfigurationTypeDef](#inputconfigurationtypedef)
  - [InputDescriptionTypeDef](#inputdescriptiontypedef)
  - [InputLambdaProcessorDescriptionTypeDef](#inputlambdaprocessordescriptiontypedef)
  - [InputLambdaProcessorTypeDef](#inputlambdaprocessortypedef)
  - [InputLambdaProcessorUpdateTypeDef](#inputlambdaprocessorupdatetypedef)
  - [InputParallelismTypeDef](#inputparallelismtypedef)
  - [InputParallelismUpdateTypeDef](#inputparallelismupdatetypedef)
  - [InputProcessingConfigurationDescriptionTypeDef](#inputprocessingconfigurationdescriptiontypedef)
  - [InputProcessingConfigurationTypeDef](#inputprocessingconfigurationtypedef)
  - [InputProcessingConfigurationUpdateTypeDef](#inputprocessingconfigurationupdatetypedef)
  - [InputSchemaUpdateTypeDef](#inputschemaupdatetypedef)
  - [InputStartingPositionConfigurationTypeDef](#inputstartingpositionconfigurationtypedef)
  - [InputTypeDef](#inputtypedef)
  - [InputUpdateTypeDef](#inputupdatetypedef)
  - [JSONMappingParametersTypeDef](#jsonmappingparameterstypedef)
  - [KinesisFirehoseInputDescriptionTypeDef](#kinesisfirehoseinputdescriptiontypedef)
  - [KinesisFirehoseInputTypeDef](#kinesisfirehoseinputtypedef)
  - [KinesisFirehoseInputUpdateTypeDef](#kinesisfirehoseinputupdatetypedef)
  - [KinesisFirehoseOutputDescriptionTypeDef](#kinesisfirehoseoutputdescriptiontypedef)
  - [KinesisFirehoseOutputTypeDef](#kinesisfirehoseoutputtypedef)
  - [KinesisFirehoseOutputUpdateTypeDef](#kinesisfirehoseoutputupdatetypedef)
  - [KinesisStreamsInputDescriptionTypeDef](#kinesisstreamsinputdescriptiontypedef)
  - [KinesisStreamsInputTypeDef](#kinesisstreamsinputtypedef)
  - [KinesisStreamsInputUpdateTypeDef](#kinesisstreamsinputupdatetypedef)
  - [KinesisStreamsOutputDescriptionTypeDef](#kinesisstreamsoutputdescriptiontypedef)
  - [KinesisStreamsOutputTypeDef](#kinesisstreamsoutputtypedef)
  - [KinesisStreamsOutputUpdateTypeDef](#kinesisstreamsoutputupdatetypedef)
  - [LambdaOutputDescriptionTypeDef](#lambdaoutputdescriptiontypedef)
  - [LambdaOutputTypeDef](#lambdaoutputtypedef)
  - [LambdaOutputUpdateTypeDef](#lambdaoutputupdatetypedef)
  - [ListApplicationsRequestRequestTypeDef](#listapplicationsrequestrequesttypedef)
  - [ListApplicationsResponseTypeDef](#listapplicationsresponsetypedef)
  - [ListTagsForResourceRequestRequestTypeDef](#listtagsforresourcerequestrequesttypedef)
  - [ListTagsForResourceResponseTypeDef](#listtagsforresourceresponsetypedef)
  - [MappingParametersTypeDef](#mappingparameterstypedef)
  - [OutputDescriptionTypeDef](#outputdescriptiontypedef)
  - [OutputTypeDef](#outputtypedef)
  - [OutputUpdateTypeDef](#outputupdatetypedef)
  - [RecordColumnTypeDef](#recordcolumntypedef)
  - [RecordFormatTypeDef](#recordformattypedef)
  - [ReferenceDataSourceDescriptionTypeDef](#referencedatasourcedescriptiontypedef)
  - [ReferenceDataSourceTypeDef](#referencedatasourcetypedef)
  - [ReferenceDataSourceUpdateTypeDef](#referencedatasourceupdatetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [S3ConfigurationTypeDef](#s3configurationtypedef)
  - [S3ReferenceDataSourceDescriptionTypeDef](#s3referencedatasourcedescriptiontypedef)
  - [S3ReferenceDataSourceTypeDef](#s3referencedatasourcetypedef)
  - [S3ReferenceDataSourceUpdateTypeDef](#s3referencedatasourceupdatetypedef)
  - [SourceSchemaTypeDef](#sourceschematypedef)
  - [StartApplicationRequestRequestTypeDef](#startapplicationrequestrequesttypedef)
  - [StopApplicationRequestRequestTypeDef](#stopapplicationrequestrequesttypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateApplicationRequestRequestTypeDef](#updateapplicationrequestrequesttypedef)

<a id="addapplicationcloudwatchloggingoptionrequestrequesttypedef"></a>

## AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import AddApplicationCloudWatchLoggingOptionRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `CloudWatchLoggingOption`:
  [CloudWatchLoggingOptionTypeDef](./type_defs.md#cloudwatchloggingoptiontypedef)

<a id="addapplicationinputprocessingconfigurationrequestrequesttypedef"></a>

## AddApplicationInputProcessingConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import AddApplicationInputProcessingConfigurationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `InputId`: `str`
- `InputProcessingConfiguration`:
  [InputProcessingConfigurationTypeDef](./type_defs.md#inputprocessingconfigurationtypedef)

<a id="addapplicationinputrequestrequesttypedef"></a>

## AddApplicationInputRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import AddApplicationInputRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `Input`: [InputTypeDef](./type_defs.md#inputtypedef)

<a id="addapplicationoutputrequestrequesttypedef"></a>

## AddApplicationOutputRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import AddApplicationOutputRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `Output`: [OutputTypeDef](./type_defs.md#outputtypedef)

<a id="addapplicationreferencedatasourcerequestrequesttypedef"></a>

## AddApplicationReferenceDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import AddApplicationReferenceDataSourceRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `ReferenceDataSource`:
  [ReferenceDataSourceTypeDef](./type_defs.md#referencedatasourcetypedef)

<a id="applicationdetailtypedef"></a>

## ApplicationDetailTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ApplicationDetailTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `ApplicationARN`: `str`
- `ApplicationStatus`:
  [ApplicationStatusType](./literals.md#applicationstatustype)
- `ApplicationVersionId`: `int`

Optional fields:

- `ApplicationDescription`: `str`
- `CreateTimestamp`: `datetime`
- `LastUpdateTimestamp`: `datetime`
- `InputDescriptions`:
  `List`\[[InputDescriptionTypeDef](./type_defs.md#inputdescriptiontypedef)\]
- `OutputDescriptions`:
  `List`\[[OutputDescriptionTypeDef](./type_defs.md#outputdescriptiontypedef)\]
- `ReferenceDataSourceDescriptions`:
  `List`\[[ReferenceDataSourceDescriptionTypeDef](./type_defs.md#referencedatasourcedescriptiontypedef)\]
- `CloudWatchLoggingOptionDescriptions`:
  `List`\[[CloudWatchLoggingOptionDescriptionTypeDef](./type_defs.md#cloudwatchloggingoptiondescriptiontypedef)\]
- `ApplicationCode`: `str`

<a id="applicationsummarytypedef"></a>

## ApplicationSummaryTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ApplicationSummaryTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `ApplicationARN`: `str`
- `ApplicationStatus`:
  [ApplicationStatusType](./literals.md#applicationstatustype)

<a id="applicationupdatetypedef"></a>

## ApplicationUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ApplicationUpdateTypeDef
```

Optional fields:

- `InputUpdates`:
  `Sequence`\[[InputUpdateTypeDef](./type_defs.md#inputupdatetypedef)\]
- `ApplicationCodeUpdate`: `str`
- `OutputUpdates`:
  `Sequence`\[[OutputUpdateTypeDef](./type_defs.md#outputupdatetypedef)\]
- `ReferenceDataSourceUpdates`:
  `Sequence`\[[ReferenceDataSourceUpdateTypeDef](./type_defs.md#referencedatasourceupdatetypedef)\]
- `CloudWatchLoggingOptionUpdates`:
  `Sequence`\[[CloudWatchLoggingOptionUpdateTypeDef](./type_defs.md#cloudwatchloggingoptionupdatetypedef)\]

<a id="csvmappingparameterstypedef"></a>

## CSVMappingParametersTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CSVMappingParametersTypeDef
```

Required fields:

- `RecordRowDelimiter`: `str`
- `RecordColumnDelimiter`: `str`

<a id="cloudwatchloggingoptiondescriptiontypedef"></a>

## CloudWatchLoggingOptionDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CloudWatchLoggingOptionDescriptionTypeDef
```

Required fields:

- `LogStreamARN`: `str`
- `RoleARN`: `str`

Optional fields:

- `CloudWatchLoggingOptionId`: `str`

<a id="cloudwatchloggingoptiontypedef"></a>

## CloudWatchLoggingOptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CloudWatchLoggingOptionTypeDef
```

Required fields:

- `LogStreamARN`: `str`
- `RoleARN`: `str`

<a id="cloudwatchloggingoptionupdatetypedef"></a>

## CloudWatchLoggingOptionUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CloudWatchLoggingOptionUpdateTypeDef
```

Required fields:

- `CloudWatchLoggingOptionId`: `str`

Optional fields:

- `LogStreamARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="createapplicationrequestrequesttypedef"></a>

## CreateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CreateApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`

Optional fields:

- `ApplicationDescription`: `str`
- `Inputs`: `Sequence`\[[InputTypeDef](./type_defs.md#inputtypedef)\]
- `Outputs`: `Sequence`\[[OutputTypeDef](./type_defs.md#outputtypedef)\]
- `CloudWatchLoggingOptions`:
  `Sequence`\[[CloudWatchLoggingOptionTypeDef](./type_defs.md#cloudwatchloggingoptiontypedef)\]
- `ApplicationCode`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createapplicationresponsetypedef"></a>

## CreateApplicationResponseTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import CreateApplicationResponseTypeDef
```

Required fields:

- `ApplicationSummary`:
  [ApplicationSummaryTypeDef](./type_defs.md#applicationsummarytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteapplicationcloudwatchloggingoptionrequestrequesttypedef"></a>

## DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DeleteApplicationCloudWatchLoggingOptionRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `CloudWatchLoggingOptionId`: `str`

<a id="deleteapplicationinputprocessingconfigurationrequestrequesttypedef"></a>

## DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DeleteApplicationInputProcessingConfigurationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `InputId`: `str`

<a id="deleteapplicationoutputrequestrequesttypedef"></a>

## DeleteApplicationOutputRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DeleteApplicationOutputRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `OutputId`: `str`

<a id="deleteapplicationreferencedatasourcerequestrequesttypedef"></a>

## DeleteApplicationReferenceDataSourceRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DeleteApplicationReferenceDataSourceRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `ReferenceId`: `str`

<a id="deleteapplicationrequestrequesttypedef"></a>

## DeleteApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DeleteApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CreateTimestamp`: `Union`\[`datetime`, `str`\]

<a id="describeapplicationrequestrequesttypedef"></a>

## DescribeApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DescribeApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`

<a id="describeapplicationresponsetypedef"></a>

## DescribeApplicationResponseTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DescribeApplicationResponseTypeDef
```

Required fields:

- `ApplicationDetail`:
  [ApplicationDetailTypeDef](./type_defs.md#applicationdetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="destinationschematypedef"></a>

## DestinationSchemaTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DestinationSchemaTypeDef
```

Required fields:

- `RecordFormatType`:
  [RecordFormatTypeType](./literals.md#recordformattypetype)

<a id="discoverinputschemarequestrequesttypedef"></a>

## DiscoverInputSchemaRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DiscoverInputSchemaRequestRequestTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`
- `InputStartingPositionConfiguration`:
  [InputStartingPositionConfigurationTypeDef](./type_defs.md#inputstartingpositionconfigurationtypedef)
- `S3Configuration`:
  [S3ConfigurationTypeDef](./type_defs.md#s3configurationtypedef)
- `InputProcessingConfiguration`:
  [InputProcessingConfigurationTypeDef](./type_defs.md#inputprocessingconfigurationtypedef)

<a id="discoverinputschemaresponsetypedef"></a>

## DiscoverInputSchemaResponseTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import DiscoverInputSchemaResponseTypeDef
```

Required fields:

- `InputSchema`: [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)
- `ParsedInputRecords`: `List`\[`List`\[`str`\]\]
- `ProcessedInputRecords`: `List`\[`str`\]
- `RawInputRecords`: `List`\[`str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="inputconfigurationtypedef"></a>

## InputConfigurationTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputConfigurationTypeDef
```

Required fields:

- `Id`: `str`
- `InputStartingPositionConfiguration`:
  [InputStartingPositionConfigurationTypeDef](./type_defs.md#inputstartingpositionconfigurationtypedef)

<a id="inputdescriptiontypedef"></a>

## InputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputDescriptionTypeDef
```

Optional fields:

- `InputId`: `str`
- `NamePrefix`: `str`
- `InAppStreamNames`: `List`\[`str`\]
- `InputProcessingConfigurationDescription`:
  [InputProcessingConfigurationDescriptionTypeDef](./type_defs.md#inputprocessingconfigurationdescriptiontypedef)
- `KinesisStreamsInputDescription`:
  [KinesisStreamsInputDescriptionTypeDef](./type_defs.md#kinesisstreamsinputdescriptiontypedef)
- `KinesisFirehoseInputDescription`:
  [KinesisFirehoseInputDescriptionTypeDef](./type_defs.md#kinesisfirehoseinputdescriptiontypedef)
- `InputSchema`: [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)
- `InputParallelism`:
  [InputParallelismTypeDef](./type_defs.md#inputparallelismtypedef)
- `InputStartingPositionConfiguration`:
  [InputStartingPositionConfigurationTypeDef](./type_defs.md#inputstartingpositionconfigurationtypedef)

<a id="inputlambdaprocessordescriptiontypedef"></a>

## InputLambdaProcessorDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputLambdaProcessorDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="inputlambdaprocessortypedef"></a>

## InputLambdaProcessorTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputLambdaProcessorTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="inputlambdaprocessorupdatetypedef"></a>

## InputLambdaProcessorUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputLambdaProcessorUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="inputparallelismtypedef"></a>

## InputParallelismTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputParallelismTypeDef
```

Optional fields:

- `Count`: `int`

<a id="inputparallelismupdatetypedef"></a>

## InputParallelismUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputParallelismUpdateTypeDef
```

Optional fields:

- `CountUpdate`: `int`

<a id="inputprocessingconfigurationdescriptiontypedef"></a>

## InputProcessingConfigurationDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputProcessingConfigurationDescriptionTypeDef
```

Optional fields:

- `InputLambdaProcessorDescription`:
  [InputLambdaProcessorDescriptionTypeDef](./type_defs.md#inputlambdaprocessordescriptiontypedef)

<a id="inputprocessingconfigurationtypedef"></a>

## InputProcessingConfigurationTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputProcessingConfigurationTypeDef
```

Required fields:

- `InputLambdaProcessor`:
  [InputLambdaProcessorTypeDef](./type_defs.md#inputlambdaprocessortypedef)

<a id="inputprocessingconfigurationupdatetypedef"></a>

## InputProcessingConfigurationUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputProcessingConfigurationUpdateTypeDef
```

Required fields:

- `InputLambdaProcessorUpdate`:
  [InputLambdaProcessorUpdateTypeDef](./type_defs.md#inputlambdaprocessorupdatetypedef)

<a id="inputschemaupdatetypedef"></a>

## InputSchemaUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputSchemaUpdateTypeDef
```

Optional fields:

- `RecordFormatUpdate`:
  [RecordFormatTypeDef](./type_defs.md#recordformattypedef)
- `RecordEncodingUpdate`: `str`
- `RecordColumnUpdates`:
  `Sequence`\[[RecordColumnTypeDef](./type_defs.md#recordcolumntypedef)\]

<a id="inputstartingpositionconfigurationtypedef"></a>

## InputStartingPositionConfigurationTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputStartingPositionConfigurationTypeDef
```

Optional fields:

- `InputStartingPosition`:
  [InputStartingPositionType](./literals.md#inputstartingpositiontype)

<a id="inputtypedef"></a>

## InputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputTypeDef
```

Required fields:

- `NamePrefix`: `str`
- `InputSchema`: [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)

Optional fields:

- `InputProcessingConfiguration`:
  [InputProcessingConfigurationTypeDef](./type_defs.md#inputprocessingconfigurationtypedef)
- `KinesisStreamsInput`:
  [KinesisStreamsInputTypeDef](./type_defs.md#kinesisstreamsinputtypedef)
- `KinesisFirehoseInput`:
  [KinesisFirehoseInputTypeDef](./type_defs.md#kinesisfirehoseinputtypedef)
- `InputParallelism`:
  [InputParallelismTypeDef](./type_defs.md#inputparallelismtypedef)

<a id="inputupdatetypedef"></a>

## InputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import InputUpdateTypeDef
```

Required fields:

- `InputId`: `str`

Optional fields:

- `NamePrefixUpdate`: `str`
- `InputProcessingConfigurationUpdate`:
  [InputProcessingConfigurationUpdateTypeDef](./type_defs.md#inputprocessingconfigurationupdatetypedef)
- `KinesisStreamsInputUpdate`:
  [KinesisStreamsInputUpdateTypeDef](./type_defs.md#kinesisstreamsinputupdatetypedef)
- `KinesisFirehoseInputUpdate`:
  [KinesisFirehoseInputUpdateTypeDef](./type_defs.md#kinesisfirehoseinputupdatetypedef)
- `InputSchemaUpdate`:
  [InputSchemaUpdateTypeDef](./type_defs.md#inputschemaupdatetypedef)
- `InputParallelismUpdate`:
  [InputParallelismUpdateTypeDef](./type_defs.md#inputparallelismupdatetypedef)

<a id="jsonmappingparameterstypedef"></a>

## JSONMappingParametersTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import JSONMappingParametersTypeDef
```

Required fields:

- `RecordRowPath`: `str`

<a id="kinesisfirehoseinputdescriptiontypedef"></a>

## KinesisFirehoseInputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseInputDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisfirehoseinputtypedef"></a>

## KinesisFirehoseInputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseInputTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisfirehoseinputupdatetypedef"></a>

## KinesisFirehoseInputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseInputUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="kinesisfirehoseoutputdescriptiontypedef"></a>

## KinesisFirehoseOutputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseOutputDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisfirehoseoutputtypedef"></a>

## KinesisFirehoseOutputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseOutputTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisfirehoseoutputupdatetypedef"></a>

## KinesisFirehoseOutputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisFirehoseOutputUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="kinesisstreamsinputdescriptiontypedef"></a>

## KinesisStreamsInputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsInputDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisstreamsinputtypedef"></a>

## KinesisStreamsInputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsInputTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisstreamsinputupdatetypedef"></a>

## KinesisStreamsInputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsInputUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="kinesisstreamsoutputdescriptiontypedef"></a>

## KinesisStreamsOutputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsOutputDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisstreamsoutputtypedef"></a>

## KinesisStreamsOutputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsOutputTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="kinesisstreamsoutputupdatetypedef"></a>

## KinesisStreamsOutputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import KinesisStreamsOutputUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="lambdaoutputdescriptiontypedef"></a>

## LambdaOutputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import LambdaOutputDescriptionTypeDef
```

Optional fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="lambdaoutputtypedef"></a>

## LambdaOutputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import LambdaOutputTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `RoleARN`: `str`

<a id="lambdaoutputupdatetypedef"></a>

## LambdaOutputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import LambdaOutputUpdateTypeDef
```

Optional fields:

- `ResourceARNUpdate`: `str`
- `RoleARNUpdate`: `str`

<a id="listapplicationsrequestrequesttypedef"></a>

## ListApplicationsRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ListApplicationsRequestRequestTypeDef
```

Optional fields:

- `Limit`: `int`
- `ExclusiveStartApplicationName`: `str`

<a id="listapplicationsresponsetypedef"></a>

## ListApplicationsResponseTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ListApplicationsResponseTypeDef
```

Required fields:

- `ApplicationSummaries`:
  `List`\[[ApplicationSummaryTypeDef](./type_defs.md#applicationsummarytypedef)\]
- `HasMoreApplications`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsforresourcerequestrequesttypedef"></a>

## ListTagsForResourceRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ListTagsForResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`

<a id="listtagsforresourceresponsetypedef"></a>

## ListTagsForResourceResponseTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ListTagsForResourceResponseTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="mappingparameterstypedef"></a>

## MappingParametersTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import MappingParametersTypeDef
```

Optional fields:

- `JSONMappingParameters`:
  [JSONMappingParametersTypeDef](./type_defs.md#jsonmappingparameterstypedef)
- `CSVMappingParameters`:
  [CSVMappingParametersTypeDef](./type_defs.md#csvmappingparameterstypedef)

<a id="outputdescriptiontypedef"></a>

## OutputDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import OutputDescriptionTypeDef
```

Optional fields:

- `OutputId`: `str`
- `Name`: `str`
- `KinesisStreamsOutputDescription`:
  [KinesisStreamsOutputDescriptionTypeDef](./type_defs.md#kinesisstreamsoutputdescriptiontypedef)
- `KinesisFirehoseOutputDescription`:
  [KinesisFirehoseOutputDescriptionTypeDef](./type_defs.md#kinesisfirehoseoutputdescriptiontypedef)
- `LambdaOutputDescription`:
  [LambdaOutputDescriptionTypeDef](./type_defs.md#lambdaoutputdescriptiontypedef)
- `DestinationSchema`:
  [DestinationSchemaTypeDef](./type_defs.md#destinationschematypedef)

<a id="outputtypedef"></a>

## OutputTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import OutputTypeDef
```

Required fields:

- `Name`: `str`
- `DestinationSchema`:
  [DestinationSchemaTypeDef](./type_defs.md#destinationschematypedef)

Optional fields:

- `KinesisStreamsOutput`:
  [KinesisStreamsOutputTypeDef](./type_defs.md#kinesisstreamsoutputtypedef)
- `KinesisFirehoseOutput`:
  [KinesisFirehoseOutputTypeDef](./type_defs.md#kinesisfirehoseoutputtypedef)
- `LambdaOutput`: [LambdaOutputTypeDef](./type_defs.md#lambdaoutputtypedef)

<a id="outputupdatetypedef"></a>

## OutputUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import OutputUpdateTypeDef
```

Required fields:

- `OutputId`: `str`

Optional fields:

- `NameUpdate`: `str`
- `KinesisStreamsOutputUpdate`:
  [KinesisStreamsOutputUpdateTypeDef](./type_defs.md#kinesisstreamsoutputupdatetypedef)
- `KinesisFirehoseOutputUpdate`:
  [KinesisFirehoseOutputUpdateTypeDef](./type_defs.md#kinesisfirehoseoutputupdatetypedef)
- `LambdaOutputUpdate`:
  [LambdaOutputUpdateTypeDef](./type_defs.md#lambdaoutputupdatetypedef)
- `DestinationSchemaUpdate`:
  [DestinationSchemaTypeDef](./type_defs.md#destinationschematypedef)

<a id="recordcolumntypedef"></a>

## RecordColumnTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import RecordColumnTypeDef
```

Required fields:

- `Name`: `str`
- `SqlType`: `str`

Optional fields:

- `Mapping`: `str`

<a id="recordformattypedef"></a>

## RecordFormatTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import RecordFormatTypeDef
```

Required fields:

- `RecordFormatType`:
  [RecordFormatTypeType](./literals.md#recordformattypetype)

Optional fields:

- `MappingParameters`:
  [MappingParametersTypeDef](./type_defs.md#mappingparameterstypedef)

<a id="referencedatasourcedescriptiontypedef"></a>

## ReferenceDataSourceDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ReferenceDataSourceDescriptionTypeDef
```

Required fields:

- `ReferenceId`: `str`
- `TableName`: `str`
- `S3ReferenceDataSourceDescription`:
  [S3ReferenceDataSourceDescriptionTypeDef](./type_defs.md#s3referencedatasourcedescriptiontypedef)

Optional fields:

- `ReferenceSchema`: [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)

<a id="referencedatasourcetypedef"></a>

## ReferenceDataSourceTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ReferenceDataSourceTypeDef
```

Required fields:

- `TableName`: `str`
- `ReferenceSchema`: [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)

Optional fields:

- `S3ReferenceDataSource`:
  [S3ReferenceDataSourceTypeDef](./type_defs.md#s3referencedatasourcetypedef)

<a id="referencedatasourceupdatetypedef"></a>

## ReferenceDataSourceUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ReferenceDataSourceUpdateTypeDef
```

Required fields:

- `ReferenceId`: `str`

Optional fields:

- `TableNameUpdate`: `str`
- `S3ReferenceDataSourceUpdate`:
  [S3ReferenceDataSourceUpdateTypeDef](./type_defs.md#s3referencedatasourceupdatetypedef)
- `ReferenceSchemaUpdate`:
  [SourceSchemaTypeDef](./type_defs.md#sourceschematypedef)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="s3configurationtypedef"></a>

## S3ConfigurationTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import S3ConfigurationTypeDef
```

Required fields:

- `RoleARN`: `str`
- `BucketARN`: `str`
- `FileKey`: `str`

<a id="s3referencedatasourcedescriptiontypedef"></a>

## S3ReferenceDataSourceDescriptionTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import S3ReferenceDataSourceDescriptionTypeDef
```

Required fields:

- `BucketARN`: `str`
- `FileKey`: `str`
- `ReferenceRoleARN`: `str`

<a id="s3referencedatasourcetypedef"></a>

## S3ReferenceDataSourceTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import S3ReferenceDataSourceTypeDef
```

Required fields:

- `BucketARN`: `str`
- `FileKey`: `str`
- `ReferenceRoleARN`: `str`

<a id="s3referencedatasourceupdatetypedef"></a>

## S3ReferenceDataSourceUpdateTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import S3ReferenceDataSourceUpdateTypeDef
```

Optional fields:

- `BucketARNUpdate`: `str`
- `FileKeyUpdate`: `str`
- `ReferenceRoleARNUpdate`: `str`

<a id="sourceschematypedef"></a>

## SourceSchemaTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import SourceSchemaTypeDef
```

Required fields:

- `RecordFormat`: [RecordFormatTypeDef](./type_defs.md#recordformattypedef)
- `RecordColumns`:
  `Sequence`\[[RecordColumnTypeDef](./type_defs.md#recordcolumntypedef)\]

Optional fields:

- `RecordEncoding`: `str`

<a id="startapplicationrequestrequesttypedef"></a>

## StartApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import StartApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `InputConfigurations`:
  `Sequence`\[[InputConfigurationTypeDef](./type_defs.md#inputconfigurationtypedef)\]

<a id="stopapplicationrequestrequesttypedef"></a>

## StopApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import StopApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`

Optional fields:

- `Value`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `ResourceARN`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="updateapplicationrequestrequesttypedef"></a>

## UpdateApplicationRequestRequestTypeDef

```python
from types_aiobotocore_kinesisanalytics.type_defs import UpdateApplicationRequestRequestTypeDef
```

Required fields:

- `ApplicationName`: `str`
- `CurrentApplicationVersionId`: `int`
- `ApplicationUpdate`:
  [ApplicationUpdateTypeDef](./type_defs.md#applicationupdatetypedef)
