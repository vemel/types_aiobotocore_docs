<a id="typed-dictionaries-for-aiobotocore-sagemaker-module"></a>

# Typed dictionaries for aiobotocore SageMaker module

> [Index](../README.md) > [SageMaker](./README.md) > Typed dictionaries

Auto-generated documentation for
[SageMaker](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker.html#SageMaker)
type annotations stubs module
[types-aiobotocore-sagemaker](https://pypi.org/project/types-aiobotocore-sagemaker/).

- [Typed dictionaries for aiobotocore SageMaker module](#typed-dictionaries-for-aiobotocore-sagemaker-module)
  - [ActionSourceTypeDef](#actionsourcetypedef)
  - [ActionSummaryTypeDef](#actionsummarytypedef)
  - [AddAssociationRequestRequestTypeDef](#addassociationrequestrequesttypedef)
  - [AddAssociationResponseTypeDef](#addassociationresponsetypedef)
  - [AddTagsInputRequestTypeDef](#addtagsinputrequesttypedef)
  - [AddTagsOutputTypeDef](#addtagsoutputtypedef)
  - [AdditionalInferenceSpecificationDefinitionTypeDef](#additionalinferencespecificationdefinitiontypedef)
  - [AgentVersionTypeDef](#agentversiontypedef)
  - [AlarmTypeDef](#alarmtypedef)
  - [AlgorithmSpecificationTypeDef](#algorithmspecificationtypedef)
  - [AlgorithmStatusDetailsTypeDef](#algorithmstatusdetailstypedef)
  - [AlgorithmStatusItemTypeDef](#algorithmstatusitemtypedef)
  - [AlgorithmSummaryTypeDef](#algorithmsummarytypedef)
  - [AlgorithmValidationProfileTypeDef](#algorithmvalidationprofiletypedef)
  - [AlgorithmValidationSpecificationTypeDef](#algorithmvalidationspecificationtypedef)
  - [AnnotationConsolidationConfigTypeDef](#annotationconsolidationconfigtypedef)
  - [AppDetailsTypeDef](#appdetailstypedef)
  - [AppImageConfigDetailsTypeDef](#appimageconfigdetailstypedef)
  - [AppSpecificationTypeDef](#appspecificationtypedef)
  - [ArtifactSourceTypeDef](#artifactsourcetypedef)
  - [ArtifactSourceTypeTypeDef](#artifactsourcetypetypedef)
  - [ArtifactSummaryTypeDef](#artifactsummarytypedef)
  - [AssociateTrialComponentRequestRequestTypeDef](#associatetrialcomponentrequestrequesttypedef)
  - [AssociateTrialComponentResponseTypeDef](#associatetrialcomponentresponsetypedef)
  - [AssociationSummaryTypeDef](#associationsummarytypedef)
  - [AsyncInferenceClientConfigTypeDef](#asyncinferenceclientconfigtypedef)
  - [AsyncInferenceConfigTypeDef](#asyncinferenceconfigtypedef)
  - [AsyncInferenceNotificationConfigTypeDef](#asyncinferencenotificationconfigtypedef)
  - [AsyncInferenceOutputConfigTypeDef](#asyncinferenceoutputconfigtypedef)
  - [AthenaDatasetDefinitionTypeDef](#athenadatasetdefinitiontypedef)
  - [AutoMLCandidateStepTypeDef](#automlcandidatesteptypedef)
  - [AutoMLCandidateTypeDef](#automlcandidatetypedef)
  - [AutoMLChannelTypeDef](#automlchanneltypedef)
  - [AutoMLContainerDefinitionTypeDef](#automlcontainerdefinitiontypedef)
  - [AutoMLDataSourceTypeDef](#automldatasourcetypedef)
  - [AutoMLJobArtifactsTypeDef](#automljobartifactstypedef)
  - [AutoMLJobCompletionCriteriaTypeDef](#automljobcompletioncriteriatypedef)
  - [AutoMLJobConfigTypeDef](#automljobconfigtypedef)
  - [AutoMLJobObjectiveTypeDef](#automljobobjectivetypedef)
  - [AutoMLJobSummaryTypeDef](#automljobsummarytypedef)
  - [AutoMLOutputDataConfigTypeDef](#automloutputdataconfigtypedef)
  - [AutoMLPartialFailureReasonTypeDef](#automlpartialfailurereasontypedef)
  - [AutoMLS3DataSourceTypeDef](#automls3datasourcetypedef)
  - [AutoMLSecurityConfigTypeDef](#automlsecurityconfigtypedef)
  - [AutoRollbackConfigTypeDef](#autorollbackconfigtypedef)
  - [BatchDescribeModelPackageErrorTypeDef](#batchdescribemodelpackageerrortypedef)
  - [BatchDescribeModelPackageInputRequestTypeDef](#batchdescribemodelpackageinputrequesttypedef)
  - [BatchDescribeModelPackageOutputTypeDef](#batchdescribemodelpackageoutputtypedef)
  - [BatchDescribeModelPackageSummaryTypeDef](#batchdescribemodelpackagesummarytypedef)
  - [BiasTypeDef](#biastypedef)
  - [BlueGreenUpdatePolicyTypeDef](#bluegreenupdatepolicytypedef)
  - [CacheHitResultTypeDef](#cachehitresulttypedef)
  - [CallbackStepMetadataTypeDef](#callbackstepmetadatatypedef)
  - [CandidateArtifactLocationsTypeDef](#candidateartifactlocationstypedef)
  - [CandidatePropertiesTypeDef](#candidatepropertiestypedef)
  - [CapacitySizeTypeDef](#capacitysizetypedef)
  - [CaptureContentTypeHeaderTypeDef](#capturecontenttypeheadertypedef)
  - [CaptureOptionTypeDef](#captureoptiontypedef)
  - [CategoricalParameterRangeSpecificationTypeDef](#categoricalparameterrangespecificationtypedef)
  - [CategoricalParameterRangeTypeDef](#categoricalparameterrangetypedef)
  - [CategoricalParameterTypeDef](#categoricalparametertypedef)
  - [ChannelSpecificationTypeDef](#channelspecificationtypedef)
  - [ChannelTypeDef](#channeltypedef)
  - [CheckpointConfigTypeDef](#checkpointconfigtypedef)
  - [ClarifyCheckStepMetadataTypeDef](#clarifycheckstepmetadatatypedef)
  - [CodeRepositorySummaryTypeDef](#coderepositorysummarytypedef)
  - [CognitoConfigTypeDef](#cognitoconfigtypedef)
  - [CognitoMemberDefinitionTypeDef](#cognitomemberdefinitiontypedef)
  - [CollectionConfigurationTypeDef](#collectionconfigurationtypedef)
  - [CompilationJobSummaryTypeDef](#compilationjobsummarytypedef)
  - [ConditionStepMetadataTypeDef](#conditionstepmetadatatypedef)
  - [ContainerDefinitionTypeDef](#containerdefinitiontypedef)
  - [ContextSourceTypeDef](#contextsourcetypedef)
  - [ContextSummaryTypeDef](#contextsummarytypedef)
  - [ContinuousParameterRangeSpecificationTypeDef](#continuousparameterrangespecificationtypedef)
  - [ContinuousParameterRangeTypeDef](#continuousparameterrangetypedef)
  - [CreateActionRequestRequestTypeDef](#createactionrequestrequesttypedef)
  - [CreateActionResponseTypeDef](#createactionresponsetypedef)
  - [CreateAlgorithmInputRequestTypeDef](#createalgorithminputrequesttypedef)
  - [CreateAlgorithmOutputTypeDef](#createalgorithmoutputtypedef)
  - [CreateAppImageConfigRequestRequestTypeDef](#createappimageconfigrequestrequesttypedef)
  - [CreateAppImageConfigResponseTypeDef](#createappimageconfigresponsetypedef)
  - [CreateAppRequestRequestTypeDef](#createapprequestrequesttypedef)
  - [CreateAppResponseTypeDef](#createappresponsetypedef)
  - [CreateArtifactRequestRequestTypeDef](#createartifactrequestrequesttypedef)
  - [CreateArtifactResponseTypeDef](#createartifactresponsetypedef)
  - [CreateAutoMLJobRequestRequestTypeDef](#createautomljobrequestrequesttypedef)
  - [CreateAutoMLJobResponseTypeDef](#createautomljobresponsetypedef)
  - [CreateCodeRepositoryInputRequestTypeDef](#createcoderepositoryinputrequesttypedef)
  - [CreateCodeRepositoryOutputTypeDef](#createcoderepositoryoutputtypedef)
  - [CreateCompilationJobRequestRequestTypeDef](#createcompilationjobrequestrequesttypedef)
  - [CreateCompilationJobResponseTypeDef](#createcompilationjobresponsetypedef)
  - [CreateContextRequestRequestTypeDef](#createcontextrequestrequesttypedef)
  - [CreateContextResponseTypeDef](#createcontextresponsetypedef)
  - [CreateDataQualityJobDefinitionRequestRequestTypeDef](#createdataqualityjobdefinitionrequestrequesttypedef)
  - [CreateDataQualityJobDefinitionResponseTypeDef](#createdataqualityjobdefinitionresponsetypedef)
  - [CreateDeviceFleetRequestRequestTypeDef](#createdevicefleetrequestrequesttypedef)
  - [CreateDomainRequestRequestTypeDef](#createdomainrequestrequesttypedef)
  - [CreateDomainResponseTypeDef](#createdomainresponsetypedef)
  - [CreateEdgePackagingJobRequestRequestTypeDef](#createedgepackagingjobrequestrequesttypedef)
  - [CreateEndpointConfigInputRequestTypeDef](#createendpointconfiginputrequesttypedef)
  - [CreateEndpointConfigOutputTypeDef](#createendpointconfigoutputtypedef)
  - [CreateEndpointInputRequestTypeDef](#createendpointinputrequesttypedef)
  - [CreateEndpointOutputTypeDef](#createendpointoutputtypedef)
  - [CreateExperimentRequestRequestTypeDef](#createexperimentrequestrequesttypedef)
  - [CreateExperimentResponseTypeDef](#createexperimentresponsetypedef)
  - [CreateFeatureGroupRequestRequestTypeDef](#createfeaturegrouprequestrequesttypedef)
  - [CreateFeatureGroupResponseTypeDef](#createfeaturegroupresponsetypedef)
  - [CreateFlowDefinitionRequestRequestTypeDef](#createflowdefinitionrequestrequesttypedef)
  - [CreateFlowDefinitionResponseTypeDef](#createflowdefinitionresponsetypedef)
  - [CreateHumanTaskUiRequestRequestTypeDef](#createhumantaskuirequestrequesttypedef)
  - [CreateHumanTaskUiResponseTypeDef](#createhumantaskuiresponsetypedef)
  - [CreateHyperParameterTuningJobRequestRequestTypeDef](#createhyperparametertuningjobrequestrequesttypedef)
  - [CreateHyperParameterTuningJobResponseTypeDef](#createhyperparametertuningjobresponsetypedef)
  - [CreateImageRequestRequestTypeDef](#createimagerequestrequesttypedef)
  - [CreateImageResponseTypeDef](#createimageresponsetypedef)
  - [CreateImageVersionRequestRequestTypeDef](#createimageversionrequestrequesttypedef)
  - [CreateImageVersionResponseTypeDef](#createimageversionresponsetypedef)
  - [CreateInferenceRecommendationsJobRequestRequestTypeDef](#createinferencerecommendationsjobrequestrequesttypedef)
  - [CreateInferenceRecommendationsJobResponseTypeDef](#createinferencerecommendationsjobresponsetypedef)
  - [CreateLabelingJobRequestRequestTypeDef](#createlabelingjobrequestrequesttypedef)
  - [CreateLabelingJobResponseTypeDef](#createlabelingjobresponsetypedef)
  - [CreateModelBiasJobDefinitionRequestRequestTypeDef](#createmodelbiasjobdefinitionrequestrequesttypedef)
  - [CreateModelBiasJobDefinitionResponseTypeDef](#createmodelbiasjobdefinitionresponsetypedef)
  - [CreateModelExplainabilityJobDefinitionRequestRequestTypeDef](#createmodelexplainabilityjobdefinitionrequestrequesttypedef)
  - [CreateModelExplainabilityJobDefinitionResponseTypeDef](#createmodelexplainabilityjobdefinitionresponsetypedef)
  - [CreateModelInputRequestTypeDef](#createmodelinputrequesttypedef)
  - [CreateModelOutputTypeDef](#createmodeloutputtypedef)
  - [CreateModelPackageGroupInputRequestTypeDef](#createmodelpackagegroupinputrequesttypedef)
  - [CreateModelPackageGroupOutputTypeDef](#createmodelpackagegroupoutputtypedef)
  - [CreateModelPackageInputRequestTypeDef](#createmodelpackageinputrequesttypedef)
  - [CreateModelPackageOutputTypeDef](#createmodelpackageoutputtypedef)
  - [CreateModelQualityJobDefinitionRequestRequestTypeDef](#createmodelqualityjobdefinitionrequestrequesttypedef)
  - [CreateModelQualityJobDefinitionResponseTypeDef](#createmodelqualityjobdefinitionresponsetypedef)
  - [CreateMonitoringScheduleRequestRequestTypeDef](#createmonitoringschedulerequestrequesttypedef)
  - [CreateMonitoringScheduleResponseTypeDef](#createmonitoringscheduleresponsetypedef)
  - [CreateNotebookInstanceInputRequestTypeDef](#createnotebookinstanceinputrequesttypedef)
  - [CreateNotebookInstanceLifecycleConfigInputRequestTypeDef](#createnotebookinstancelifecycleconfiginputrequesttypedef)
  - [CreateNotebookInstanceLifecycleConfigOutputTypeDef](#createnotebookinstancelifecycleconfigoutputtypedef)
  - [CreateNotebookInstanceOutputTypeDef](#createnotebookinstanceoutputtypedef)
  - [CreatePipelineRequestRequestTypeDef](#createpipelinerequestrequesttypedef)
  - [CreatePipelineResponseTypeDef](#createpipelineresponsetypedef)
  - [CreatePresignedDomainUrlRequestRequestTypeDef](#createpresigneddomainurlrequestrequesttypedef)
  - [CreatePresignedDomainUrlResponseTypeDef](#createpresigneddomainurlresponsetypedef)
  - [CreatePresignedNotebookInstanceUrlInputRequestTypeDef](#createpresignednotebookinstanceurlinputrequesttypedef)
  - [CreatePresignedNotebookInstanceUrlOutputTypeDef](#createpresignednotebookinstanceurloutputtypedef)
  - [CreateProcessingJobRequestRequestTypeDef](#createprocessingjobrequestrequesttypedef)
  - [CreateProcessingJobResponseTypeDef](#createprocessingjobresponsetypedef)
  - [CreateProjectInputRequestTypeDef](#createprojectinputrequesttypedef)
  - [CreateProjectOutputTypeDef](#createprojectoutputtypedef)
  - [CreateStudioLifecycleConfigRequestRequestTypeDef](#createstudiolifecycleconfigrequestrequesttypedef)
  - [CreateStudioLifecycleConfigResponseTypeDef](#createstudiolifecycleconfigresponsetypedef)
  - [CreateTrainingJobRequestRequestTypeDef](#createtrainingjobrequestrequesttypedef)
  - [CreateTrainingJobResponseTypeDef](#createtrainingjobresponsetypedef)
  - [CreateTransformJobRequestRequestTypeDef](#createtransformjobrequestrequesttypedef)
  - [CreateTransformJobResponseTypeDef](#createtransformjobresponsetypedef)
  - [CreateTrialComponentRequestRequestTypeDef](#createtrialcomponentrequestrequesttypedef)
  - [CreateTrialComponentResponseTypeDef](#createtrialcomponentresponsetypedef)
  - [CreateTrialRequestRequestTypeDef](#createtrialrequestrequesttypedef)
  - [CreateTrialResponseTypeDef](#createtrialresponsetypedef)
  - [CreateUserProfileRequestRequestTypeDef](#createuserprofilerequestrequesttypedef)
  - [CreateUserProfileResponseTypeDef](#createuserprofileresponsetypedef)
  - [CreateWorkforceRequestRequestTypeDef](#createworkforcerequestrequesttypedef)
  - [CreateWorkforceResponseTypeDef](#createworkforceresponsetypedef)
  - [CreateWorkteamRequestRequestTypeDef](#createworkteamrequestrequesttypedef)
  - [CreateWorkteamResponseTypeDef](#createworkteamresponsetypedef)
  - [CustomImageTypeDef](#customimagetypedef)
  - [DataCaptureConfigSummaryTypeDef](#datacaptureconfigsummarytypedef)
  - [DataCaptureConfigTypeDef](#datacaptureconfigtypedef)
  - [DataCatalogConfigTypeDef](#datacatalogconfigtypedef)
  - [DataProcessingTypeDef](#dataprocessingtypedef)
  - [DataQualityAppSpecificationTypeDef](#dataqualityappspecificationtypedef)
  - [DataQualityBaselineConfigTypeDef](#dataqualitybaselineconfigtypedef)
  - [DataQualityJobInputTypeDef](#dataqualityjobinputtypedef)
  - [DataSourceTypeDef](#datasourcetypedef)
  - [DatasetDefinitionTypeDef](#datasetdefinitiontypedef)
  - [DebugHookConfigTypeDef](#debughookconfigtypedef)
  - [DebugRuleConfigurationTypeDef](#debugruleconfigurationtypedef)
  - [DebugRuleEvaluationStatusTypeDef](#debugruleevaluationstatustypedef)
  - [DeleteActionRequestRequestTypeDef](#deleteactionrequestrequesttypedef)
  - [DeleteActionResponseTypeDef](#deleteactionresponsetypedef)
  - [DeleteAlgorithmInputRequestTypeDef](#deletealgorithminputrequesttypedef)
  - [DeleteAppImageConfigRequestRequestTypeDef](#deleteappimageconfigrequestrequesttypedef)
  - [DeleteAppRequestRequestTypeDef](#deleteapprequestrequesttypedef)
  - [DeleteArtifactRequestRequestTypeDef](#deleteartifactrequestrequesttypedef)
  - [DeleteArtifactResponseTypeDef](#deleteartifactresponsetypedef)
  - [DeleteAssociationRequestRequestTypeDef](#deleteassociationrequestrequesttypedef)
  - [DeleteAssociationResponseTypeDef](#deleteassociationresponsetypedef)
  - [DeleteCodeRepositoryInputRequestTypeDef](#deletecoderepositoryinputrequesttypedef)
  - [DeleteContextRequestRequestTypeDef](#deletecontextrequestrequesttypedef)
  - [DeleteContextResponseTypeDef](#deletecontextresponsetypedef)
  - [DeleteDataQualityJobDefinitionRequestRequestTypeDef](#deletedataqualityjobdefinitionrequestrequesttypedef)
  - [DeleteDeviceFleetRequestRequestTypeDef](#deletedevicefleetrequestrequesttypedef)
  - [DeleteDomainRequestRequestTypeDef](#deletedomainrequestrequesttypedef)
  - [DeleteEndpointConfigInputRequestTypeDef](#deleteendpointconfiginputrequesttypedef)
  - [DeleteEndpointInputRequestTypeDef](#deleteendpointinputrequesttypedef)
  - [DeleteExperimentRequestRequestTypeDef](#deleteexperimentrequestrequesttypedef)
  - [DeleteExperimentResponseTypeDef](#deleteexperimentresponsetypedef)
  - [DeleteFeatureGroupRequestRequestTypeDef](#deletefeaturegrouprequestrequesttypedef)
  - [DeleteFlowDefinitionRequestRequestTypeDef](#deleteflowdefinitionrequestrequesttypedef)
  - [DeleteHumanTaskUiRequestRequestTypeDef](#deletehumantaskuirequestrequesttypedef)
  - [DeleteImageRequestRequestTypeDef](#deleteimagerequestrequesttypedef)
  - [DeleteImageVersionRequestRequestTypeDef](#deleteimageversionrequestrequesttypedef)
  - [DeleteModelBiasJobDefinitionRequestRequestTypeDef](#deletemodelbiasjobdefinitionrequestrequesttypedef)
  - [DeleteModelExplainabilityJobDefinitionRequestRequestTypeDef](#deletemodelexplainabilityjobdefinitionrequestrequesttypedef)
  - [DeleteModelInputRequestTypeDef](#deletemodelinputrequesttypedef)
  - [DeleteModelPackageGroupInputRequestTypeDef](#deletemodelpackagegroupinputrequesttypedef)
  - [DeleteModelPackageGroupPolicyInputRequestTypeDef](#deletemodelpackagegrouppolicyinputrequesttypedef)
  - [DeleteModelPackageInputRequestTypeDef](#deletemodelpackageinputrequesttypedef)
  - [DeleteModelQualityJobDefinitionRequestRequestTypeDef](#deletemodelqualityjobdefinitionrequestrequesttypedef)
  - [DeleteMonitoringScheduleRequestRequestTypeDef](#deletemonitoringschedulerequestrequesttypedef)
  - [DeleteNotebookInstanceInputRequestTypeDef](#deletenotebookinstanceinputrequesttypedef)
  - [DeleteNotebookInstanceLifecycleConfigInputRequestTypeDef](#deletenotebookinstancelifecycleconfiginputrequesttypedef)
  - [DeletePipelineRequestRequestTypeDef](#deletepipelinerequestrequesttypedef)
  - [DeletePipelineResponseTypeDef](#deletepipelineresponsetypedef)
  - [DeleteProjectInputRequestTypeDef](#deleteprojectinputrequesttypedef)
  - [DeleteStudioLifecycleConfigRequestRequestTypeDef](#deletestudiolifecycleconfigrequestrequesttypedef)
  - [DeleteTagsInputRequestTypeDef](#deletetagsinputrequesttypedef)
  - [DeleteTrialComponentRequestRequestTypeDef](#deletetrialcomponentrequestrequesttypedef)
  - [DeleteTrialComponentResponseTypeDef](#deletetrialcomponentresponsetypedef)
  - [DeleteTrialRequestRequestTypeDef](#deletetrialrequestrequesttypedef)
  - [DeleteTrialResponseTypeDef](#deletetrialresponsetypedef)
  - [DeleteUserProfileRequestRequestTypeDef](#deleteuserprofilerequestrequesttypedef)
  - [DeleteWorkforceRequestRequestTypeDef](#deleteworkforcerequestrequesttypedef)
  - [DeleteWorkteamRequestRequestTypeDef](#deleteworkteamrequestrequesttypedef)
  - [DeleteWorkteamResponseTypeDef](#deleteworkteamresponsetypedef)
  - [DeployedImageTypeDef](#deployedimagetypedef)
  - [DeploymentConfigTypeDef](#deploymentconfigtypedef)
  - [DeregisterDevicesRequestRequestTypeDef](#deregisterdevicesrequestrequesttypedef)
  - [DescribeActionRequestRequestTypeDef](#describeactionrequestrequesttypedef)
  - [DescribeActionResponseTypeDef](#describeactionresponsetypedef)
  - [DescribeAlgorithmInputRequestTypeDef](#describealgorithminputrequesttypedef)
  - [DescribeAlgorithmOutputTypeDef](#describealgorithmoutputtypedef)
  - [DescribeAppImageConfigRequestRequestTypeDef](#describeappimageconfigrequestrequesttypedef)
  - [DescribeAppImageConfigResponseTypeDef](#describeappimageconfigresponsetypedef)
  - [DescribeAppRequestRequestTypeDef](#describeapprequestrequesttypedef)
  - [DescribeAppResponseTypeDef](#describeappresponsetypedef)
  - [DescribeArtifactRequestRequestTypeDef](#describeartifactrequestrequesttypedef)
  - [DescribeArtifactResponseTypeDef](#describeartifactresponsetypedef)
  - [DescribeAutoMLJobRequestRequestTypeDef](#describeautomljobrequestrequesttypedef)
  - [DescribeAutoMLJobResponseTypeDef](#describeautomljobresponsetypedef)
  - [DescribeCodeRepositoryInputRequestTypeDef](#describecoderepositoryinputrequesttypedef)
  - [DescribeCodeRepositoryOutputTypeDef](#describecoderepositoryoutputtypedef)
  - [DescribeCompilationJobRequestRequestTypeDef](#describecompilationjobrequestrequesttypedef)
  - [DescribeCompilationJobResponseTypeDef](#describecompilationjobresponsetypedef)
  - [DescribeContextRequestRequestTypeDef](#describecontextrequestrequesttypedef)
  - [DescribeContextResponseTypeDef](#describecontextresponsetypedef)
  - [DescribeDataQualityJobDefinitionRequestRequestTypeDef](#describedataqualityjobdefinitionrequestrequesttypedef)
  - [DescribeDataQualityJobDefinitionResponseTypeDef](#describedataqualityjobdefinitionresponsetypedef)
  - [DescribeDeviceFleetRequestRequestTypeDef](#describedevicefleetrequestrequesttypedef)
  - [DescribeDeviceFleetResponseTypeDef](#describedevicefleetresponsetypedef)
  - [DescribeDeviceRequestRequestTypeDef](#describedevicerequestrequesttypedef)
  - [DescribeDeviceResponseTypeDef](#describedeviceresponsetypedef)
  - [DescribeDomainRequestRequestTypeDef](#describedomainrequestrequesttypedef)
  - [DescribeDomainResponseTypeDef](#describedomainresponsetypedef)
  - [DescribeEdgePackagingJobRequestRequestTypeDef](#describeedgepackagingjobrequestrequesttypedef)
  - [DescribeEdgePackagingJobResponseTypeDef](#describeedgepackagingjobresponsetypedef)
  - [DescribeEndpointConfigInputRequestTypeDef](#describeendpointconfiginputrequesttypedef)
  - [DescribeEndpointConfigOutputTypeDef](#describeendpointconfigoutputtypedef)
  - [DescribeEndpointInputRequestTypeDef](#describeendpointinputrequesttypedef)
  - [DescribeEndpointOutputTypeDef](#describeendpointoutputtypedef)
  - [DescribeExperimentRequestRequestTypeDef](#describeexperimentrequestrequesttypedef)
  - [DescribeExperimentResponseTypeDef](#describeexperimentresponsetypedef)
  - [DescribeFeatureGroupRequestRequestTypeDef](#describefeaturegrouprequestrequesttypedef)
  - [DescribeFeatureGroupResponseTypeDef](#describefeaturegroupresponsetypedef)
  - [DescribeFlowDefinitionRequestRequestTypeDef](#describeflowdefinitionrequestrequesttypedef)
  - [DescribeFlowDefinitionResponseTypeDef](#describeflowdefinitionresponsetypedef)
  - [DescribeHumanTaskUiRequestRequestTypeDef](#describehumantaskuirequestrequesttypedef)
  - [DescribeHumanTaskUiResponseTypeDef](#describehumantaskuiresponsetypedef)
  - [DescribeHyperParameterTuningJobRequestRequestTypeDef](#describehyperparametertuningjobrequestrequesttypedef)
  - [DescribeHyperParameterTuningJobResponseTypeDef](#describehyperparametertuningjobresponsetypedef)
  - [DescribeImageRequestRequestTypeDef](#describeimagerequestrequesttypedef)
  - [DescribeImageResponseTypeDef](#describeimageresponsetypedef)
  - [DescribeImageVersionRequestRequestTypeDef](#describeimageversionrequestrequesttypedef)
  - [DescribeImageVersionResponseTypeDef](#describeimageversionresponsetypedef)
  - [DescribeInferenceRecommendationsJobRequestRequestTypeDef](#describeinferencerecommendationsjobrequestrequesttypedef)
  - [DescribeInferenceRecommendationsJobResponseTypeDef](#describeinferencerecommendationsjobresponsetypedef)
  - [DescribeLabelingJobRequestRequestTypeDef](#describelabelingjobrequestrequesttypedef)
  - [DescribeLabelingJobResponseTypeDef](#describelabelingjobresponsetypedef)
  - [DescribeLineageGroupRequestRequestTypeDef](#describelineagegrouprequestrequesttypedef)
  - [DescribeLineageGroupResponseTypeDef](#describelineagegroupresponsetypedef)
  - [DescribeModelBiasJobDefinitionRequestRequestTypeDef](#describemodelbiasjobdefinitionrequestrequesttypedef)
  - [DescribeModelBiasJobDefinitionResponseTypeDef](#describemodelbiasjobdefinitionresponsetypedef)
  - [DescribeModelExplainabilityJobDefinitionRequestRequestTypeDef](#describemodelexplainabilityjobdefinitionrequestrequesttypedef)
  - [DescribeModelExplainabilityJobDefinitionResponseTypeDef](#describemodelexplainabilityjobdefinitionresponsetypedef)
  - [DescribeModelInputRequestTypeDef](#describemodelinputrequesttypedef)
  - [DescribeModelOutputTypeDef](#describemodeloutputtypedef)
  - [DescribeModelPackageGroupInputRequestTypeDef](#describemodelpackagegroupinputrequesttypedef)
  - [DescribeModelPackageGroupOutputTypeDef](#describemodelpackagegroupoutputtypedef)
  - [DescribeModelPackageInputRequestTypeDef](#describemodelpackageinputrequesttypedef)
  - [DescribeModelPackageOutputTypeDef](#describemodelpackageoutputtypedef)
  - [DescribeModelQualityJobDefinitionRequestRequestTypeDef](#describemodelqualityjobdefinitionrequestrequesttypedef)
  - [DescribeModelQualityJobDefinitionResponseTypeDef](#describemodelqualityjobdefinitionresponsetypedef)
  - [DescribeMonitoringScheduleRequestRequestTypeDef](#describemonitoringschedulerequestrequesttypedef)
  - [DescribeMonitoringScheduleResponseTypeDef](#describemonitoringscheduleresponsetypedef)
  - [DescribeNotebookInstanceInputRequestTypeDef](#describenotebookinstanceinputrequesttypedef)
  - [DescribeNotebookInstanceLifecycleConfigInputRequestTypeDef](#describenotebookinstancelifecycleconfiginputrequesttypedef)
  - [DescribeNotebookInstanceLifecycleConfigOutputTypeDef](#describenotebookinstancelifecycleconfigoutputtypedef)
  - [DescribeNotebookInstanceOutputTypeDef](#describenotebookinstanceoutputtypedef)
  - [DescribePipelineDefinitionForExecutionRequestRequestTypeDef](#describepipelinedefinitionforexecutionrequestrequesttypedef)
  - [DescribePipelineDefinitionForExecutionResponseTypeDef](#describepipelinedefinitionforexecutionresponsetypedef)
  - [DescribePipelineExecutionRequestRequestTypeDef](#describepipelineexecutionrequestrequesttypedef)
  - [DescribePipelineExecutionResponseTypeDef](#describepipelineexecutionresponsetypedef)
  - [DescribePipelineRequestRequestTypeDef](#describepipelinerequestrequesttypedef)
  - [DescribePipelineResponseTypeDef](#describepipelineresponsetypedef)
  - [DescribeProcessingJobRequestRequestTypeDef](#describeprocessingjobrequestrequesttypedef)
  - [DescribeProcessingJobResponseTypeDef](#describeprocessingjobresponsetypedef)
  - [DescribeProjectInputRequestTypeDef](#describeprojectinputrequesttypedef)
  - [DescribeProjectOutputTypeDef](#describeprojectoutputtypedef)
  - [DescribeStudioLifecycleConfigRequestRequestTypeDef](#describestudiolifecycleconfigrequestrequesttypedef)
  - [DescribeStudioLifecycleConfigResponseTypeDef](#describestudiolifecycleconfigresponsetypedef)
  - [DescribeSubscribedWorkteamRequestRequestTypeDef](#describesubscribedworkteamrequestrequesttypedef)
  - [DescribeSubscribedWorkteamResponseTypeDef](#describesubscribedworkteamresponsetypedef)
  - [DescribeTrainingJobRequestRequestTypeDef](#describetrainingjobrequestrequesttypedef)
  - [DescribeTrainingJobResponseTypeDef](#describetrainingjobresponsetypedef)
  - [DescribeTransformJobRequestRequestTypeDef](#describetransformjobrequestrequesttypedef)
  - [DescribeTransformJobResponseTypeDef](#describetransformjobresponsetypedef)
  - [DescribeTrialComponentRequestRequestTypeDef](#describetrialcomponentrequestrequesttypedef)
  - [DescribeTrialComponentResponseTypeDef](#describetrialcomponentresponsetypedef)
  - [DescribeTrialRequestRequestTypeDef](#describetrialrequestrequesttypedef)
  - [DescribeTrialResponseTypeDef](#describetrialresponsetypedef)
  - [DescribeUserProfileRequestRequestTypeDef](#describeuserprofilerequestrequesttypedef)
  - [DescribeUserProfileResponseTypeDef](#describeuserprofileresponsetypedef)
  - [DescribeWorkforceRequestRequestTypeDef](#describeworkforcerequestrequesttypedef)
  - [DescribeWorkforceResponseTypeDef](#describeworkforceresponsetypedef)
  - [DescribeWorkteamRequestRequestTypeDef](#describeworkteamrequestrequesttypedef)
  - [DescribeWorkteamResponseTypeDef](#describeworkteamresponsetypedef)
  - [DesiredWeightAndCapacityTypeDef](#desiredweightandcapacitytypedef)
  - [DeviceFleetSummaryTypeDef](#devicefleetsummarytypedef)
  - [DeviceStatsTypeDef](#devicestatstypedef)
  - [DeviceSummaryTypeDef](#devicesummarytypedef)
  - [DeviceTypeDef](#devicetypedef)
  - [DisassociateTrialComponentRequestRequestTypeDef](#disassociatetrialcomponentrequestrequesttypedef)
  - [DisassociateTrialComponentResponseTypeDef](#disassociatetrialcomponentresponsetypedef)
  - [DomainDetailsTypeDef](#domaindetailstypedef)
  - [DomainSettingsForUpdateTypeDef](#domainsettingsforupdatetypedef)
  - [DomainSettingsTypeDef](#domainsettingstypedef)
  - [DriftCheckBaselinesTypeDef](#driftcheckbaselinestypedef)
  - [DriftCheckBiasTypeDef](#driftcheckbiastypedef)
  - [DriftCheckExplainabilityTypeDef](#driftcheckexplainabilitytypedef)
  - [DriftCheckModelDataQualityTypeDef](#driftcheckmodeldataqualitytypedef)
  - [DriftCheckModelQualityTypeDef](#driftcheckmodelqualitytypedef)
  - [EMRStepMetadataTypeDef](#emrstepmetadatatypedef)
  - [EdgeModelStatTypeDef](#edgemodelstattypedef)
  - [EdgeModelSummaryTypeDef](#edgemodelsummarytypedef)
  - [EdgeModelTypeDef](#edgemodeltypedef)
  - [EdgeOutputConfigTypeDef](#edgeoutputconfigtypedef)
  - [EdgePackagingJobSummaryTypeDef](#edgepackagingjobsummarytypedef)
  - [EdgePresetDeploymentOutputTypeDef](#edgepresetdeploymentoutputtypedef)
  - [EdgeTypeDef](#edgetypedef)
  - [EndpointConfigSummaryTypeDef](#endpointconfigsummarytypedef)
  - [EndpointInputConfigurationTypeDef](#endpointinputconfigurationtypedef)
  - [EndpointInputTypeDef](#endpointinputtypedef)
  - [EndpointOutputConfigurationTypeDef](#endpointoutputconfigurationtypedef)
  - [EndpointSummaryTypeDef](#endpointsummarytypedef)
  - [EndpointTypeDef](#endpointtypedef)
  - [EnvironmentParameterRangesTypeDef](#environmentparameterrangestypedef)
  - [EnvironmentParameterTypeDef](#environmentparametertypedef)
  - [ExperimentConfigTypeDef](#experimentconfigtypedef)
  - [ExperimentSourceTypeDef](#experimentsourcetypedef)
  - [ExperimentSummaryTypeDef](#experimentsummarytypedef)
  - [ExperimentTypeDef](#experimenttypedef)
  - [ExplainabilityTypeDef](#explainabilitytypedef)
  - [FailStepMetadataTypeDef](#failstepmetadatatypedef)
  - [FeatureDefinitionTypeDef](#featuredefinitiontypedef)
  - [FeatureGroupSummaryTypeDef](#featuregroupsummarytypedef)
  - [FeatureGroupTypeDef](#featuregrouptypedef)
  - [FileSourceTypeDef](#filesourcetypedef)
  - [FileSystemConfigTypeDef](#filesystemconfigtypedef)
  - [FileSystemDataSourceTypeDef](#filesystemdatasourcetypedef)
  - [FilterTypeDef](#filtertypedef)
  - [FinalAutoMLJobObjectiveMetricTypeDef](#finalautomljobobjectivemetrictypedef)
  - [FinalHyperParameterTuningJobObjectiveMetricTypeDef](#finalhyperparametertuningjobobjectivemetrictypedef)
  - [FlowDefinitionOutputConfigTypeDef](#flowdefinitionoutputconfigtypedef)
  - [FlowDefinitionSummaryTypeDef](#flowdefinitionsummarytypedef)
  - [GetDeviceFleetReportRequestRequestTypeDef](#getdevicefleetreportrequestrequesttypedef)
  - [GetDeviceFleetReportResponseTypeDef](#getdevicefleetreportresponsetypedef)
  - [GetLineageGroupPolicyRequestRequestTypeDef](#getlineagegrouppolicyrequestrequesttypedef)
  - [GetLineageGroupPolicyResponseTypeDef](#getlineagegrouppolicyresponsetypedef)
  - [GetModelPackageGroupPolicyInputRequestTypeDef](#getmodelpackagegrouppolicyinputrequesttypedef)
  - [GetModelPackageGroupPolicyOutputTypeDef](#getmodelpackagegrouppolicyoutputtypedef)
  - [GetSagemakerServicecatalogPortfolioStatusOutputTypeDef](#getsagemakerservicecatalogportfoliostatusoutputtypedef)
  - [GetSearchSuggestionsRequestRequestTypeDef](#getsearchsuggestionsrequestrequesttypedef)
  - [GetSearchSuggestionsResponseTypeDef](#getsearchsuggestionsresponsetypedef)
  - [GitConfigForUpdateTypeDef](#gitconfigforupdatetypedef)
  - [GitConfigTypeDef](#gitconfigtypedef)
  - [HumanLoopActivationConditionsConfigTypeDef](#humanloopactivationconditionsconfigtypedef)
  - [HumanLoopActivationConfigTypeDef](#humanloopactivationconfigtypedef)
  - [HumanLoopConfigTypeDef](#humanloopconfigtypedef)
  - [HumanLoopRequestSourceTypeDef](#humanlooprequestsourcetypedef)
  - [HumanTaskConfigTypeDef](#humantaskconfigtypedef)
  - [HumanTaskUiSummaryTypeDef](#humantaskuisummarytypedef)
  - [HyperParameterAlgorithmSpecificationTypeDef](#hyperparameteralgorithmspecificationtypedef)
  - [HyperParameterSpecificationTypeDef](#hyperparameterspecificationtypedef)
  - [HyperParameterTrainingJobDefinitionTypeDef](#hyperparametertrainingjobdefinitiontypedef)
  - [HyperParameterTrainingJobSummaryTypeDef](#hyperparametertrainingjobsummarytypedef)
  - [HyperParameterTuningJobConfigTypeDef](#hyperparametertuningjobconfigtypedef)
  - [HyperParameterTuningJobObjectiveTypeDef](#hyperparametertuningjobobjectivetypedef)
  - [HyperParameterTuningJobSummaryTypeDef](#hyperparametertuningjobsummarytypedef)
  - [HyperParameterTuningJobWarmStartConfigTypeDef](#hyperparametertuningjobwarmstartconfigtypedef)
  - [ImageConfigTypeDef](#imageconfigtypedef)
  - [ImageTypeDef](#imagetypedef)
  - [ImageVersionTypeDef](#imageversiontypedef)
  - [InferenceExecutionConfigTypeDef](#inferenceexecutionconfigtypedef)
  - [InferenceRecommendationTypeDef](#inferencerecommendationtypedef)
  - [InferenceRecommendationsJobTypeDef](#inferencerecommendationsjobtypedef)
  - [InferenceSpecificationTypeDef](#inferencespecificationtypedef)
  - [InputConfigTypeDef](#inputconfigtypedef)
  - [IntegerParameterRangeSpecificationTypeDef](#integerparameterrangespecificationtypedef)
  - [IntegerParameterRangeTypeDef](#integerparameterrangetypedef)
  - [JupyterServerAppSettingsTypeDef](#jupyterserverappsettingstypedef)
  - [KernelGatewayAppSettingsTypeDef](#kernelgatewayappsettingstypedef)
  - [KernelGatewayImageConfigTypeDef](#kernelgatewayimageconfigtypedef)
  - [KernelSpecTypeDef](#kernelspectypedef)
  - [LabelCountersForWorkteamTypeDef](#labelcountersforworkteamtypedef)
  - [LabelCountersTypeDef](#labelcounterstypedef)
  - [LabelingJobAlgorithmsConfigTypeDef](#labelingjobalgorithmsconfigtypedef)
  - [LabelingJobDataAttributesTypeDef](#labelingjobdataattributestypedef)
  - [LabelingJobDataSourceTypeDef](#labelingjobdatasourcetypedef)
  - [LabelingJobForWorkteamSummaryTypeDef](#labelingjobforworkteamsummarytypedef)
  - [LabelingJobInputConfigTypeDef](#labelingjobinputconfigtypedef)
  - [LabelingJobOutputConfigTypeDef](#labelingjoboutputconfigtypedef)
  - [LabelingJobOutputTypeDef](#labelingjoboutputtypedef)
  - [LabelingJobResourceConfigTypeDef](#labelingjobresourceconfigtypedef)
  - [LabelingJobS3DataSourceTypeDef](#labelingjobs3datasourcetypedef)
  - [LabelingJobSnsDataSourceTypeDef](#labelingjobsnsdatasourcetypedef)
  - [LabelingJobStoppingConditionsTypeDef](#labelingjobstoppingconditionstypedef)
  - [LabelingJobSummaryTypeDef](#labelingjobsummarytypedef)
  - [LambdaStepMetadataTypeDef](#lambdastepmetadatatypedef)
  - [LineageGroupSummaryTypeDef](#lineagegroupsummarytypedef)
  - [ListActionsRequestRequestTypeDef](#listactionsrequestrequesttypedef)
  - [ListActionsResponseTypeDef](#listactionsresponsetypedef)
  - [ListAlgorithmsInputRequestTypeDef](#listalgorithmsinputrequesttypedef)
  - [ListAlgorithmsOutputTypeDef](#listalgorithmsoutputtypedef)
  - [ListAppImageConfigsRequestRequestTypeDef](#listappimageconfigsrequestrequesttypedef)
  - [ListAppImageConfigsResponseTypeDef](#listappimageconfigsresponsetypedef)
  - [ListAppsRequestRequestTypeDef](#listappsrequestrequesttypedef)
  - [ListAppsResponseTypeDef](#listappsresponsetypedef)
  - [ListArtifactsRequestRequestTypeDef](#listartifactsrequestrequesttypedef)
  - [ListArtifactsResponseTypeDef](#listartifactsresponsetypedef)
  - [ListAssociationsRequestRequestTypeDef](#listassociationsrequestrequesttypedef)
  - [ListAssociationsResponseTypeDef](#listassociationsresponsetypedef)
  - [ListAutoMLJobsRequestRequestTypeDef](#listautomljobsrequestrequesttypedef)
  - [ListAutoMLJobsResponseTypeDef](#listautomljobsresponsetypedef)
  - [ListCandidatesForAutoMLJobRequestRequestTypeDef](#listcandidatesforautomljobrequestrequesttypedef)
  - [ListCandidatesForAutoMLJobResponseTypeDef](#listcandidatesforautomljobresponsetypedef)
  - [ListCodeRepositoriesInputRequestTypeDef](#listcoderepositoriesinputrequesttypedef)
  - [ListCodeRepositoriesOutputTypeDef](#listcoderepositoriesoutputtypedef)
  - [ListCompilationJobsRequestRequestTypeDef](#listcompilationjobsrequestrequesttypedef)
  - [ListCompilationJobsResponseTypeDef](#listcompilationjobsresponsetypedef)
  - [ListContextsRequestRequestTypeDef](#listcontextsrequestrequesttypedef)
  - [ListContextsResponseTypeDef](#listcontextsresponsetypedef)
  - [ListDataQualityJobDefinitionsRequestRequestTypeDef](#listdataqualityjobdefinitionsrequestrequesttypedef)
  - [ListDataQualityJobDefinitionsResponseTypeDef](#listdataqualityjobdefinitionsresponsetypedef)
  - [ListDeviceFleetsRequestRequestTypeDef](#listdevicefleetsrequestrequesttypedef)
  - [ListDeviceFleetsResponseTypeDef](#listdevicefleetsresponsetypedef)
  - [ListDevicesRequestRequestTypeDef](#listdevicesrequestrequesttypedef)
  - [ListDevicesResponseTypeDef](#listdevicesresponsetypedef)
  - [ListDomainsRequestRequestTypeDef](#listdomainsrequestrequesttypedef)
  - [ListDomainsResponseTypeDef](#listdomainsresponsetypedef)
  - [ListEdgePackagingJobsRequestRequestTypeDef](#listedgepackagingjobsrequestrequesttypedef)
  - [ListEdgePackagingJobsResponseTypeDef](#listedgepackagingjobsresponsetypedef)
  - [ListEndpointConfigsInputRequestTypeDef](#listendpointconfigsinputrequesttypedef)
  - [ListEndpointConfigsOutputTypeDef](#listendpointconfigsoutputtypedef)
  - [ListEndpointsInputRequestTypeDef](#listendpointsinputrequesttypedef)
  - [ListEndpointsOutputTypeDef](#listendpointsoutputtypedef)
  - [ListExperimentsRequestRequestTypeDef](#listexperimentsrequestrequesttypedef)
  - [ListExperimentsResponseTypeDef](#listexperimentsresponsetypedef)
  - [ListFeatureGroupsRequestRequestTypeDef](#listfeaturegroupsrequestrequesttypedef)
  - [ListFeatureGroupsResponseTypeDef](#listfeaturegroupsresponsetypedef)
  - [ListFlowDefinitionsRequestRequestTypeDef](#listflowdefinitionsrequestrequesttypedef)
  - [ListFlowDefinitionsResponseTypeDef](#listflowdefinitionsresponsetypedef)
  - [ListHumanTaskUisRequestRequestTypeDef](#listhumantaskuisrequestrequesttypedef)
  - [ListHumanTaskUisResponseTypeDef](#listhumantaskuisresponsetypedef)
  - [ListHyperParameterTuningJobsRequestRequestTypeDef](#listhyperparametertuningjobsrequestrequesttypedef)
  - [ListHyperParameterTuningJobsResponseTypeDef](#listhyperparametertuningjobsresponsetypedef)
  - [ListImageVersionsRequestRequestTypeDef](#listimageversionsrequestrequesttypedef)
  - [ListImageVersionsResponseTypeDef](#listimageversionsresponsetypedef)
  - [ListImagesRequestRequestTypeDef](#listimagesrequestrequesttypedef)
  - [ListImagesResponseTypeDef](#listimagesresponsetypedef)
  - [ListInferenceRecommendationsJobsRequestRequestTypeDef](#listinferencerecommendationsjobsrequestrequesttypedef)
  - [ListInferenceRecommendationsJobsResponseTypeDef](#listinferencerecommendationsjobsresponsetypedef)
  - [ListLabelingJobsForWorkteamRequestRequestTypeDef](#listlabelingjobsforworkteamrequestrequesttypedef)
  - [ListLabelingJobsForWorkteamResponseTypeDef](#listlabelingjobsforworkteamresponsetypedef)
  - [ListLabelingJobsRequestRequestTypeDef](#listlabelingjobsrequestrequesttypedef)
  - [ListLabelingJobsResponseTypeDef](#listlabelingjobsresponsetypedef)
  - [ListLineageGroupsRequestRequestTypeDef](#listlineagegroupsrequestrequesttypedef)
  - [ListLineageGroupsResponseTypeDef](#listlineagegroupsresponsetypedef)
  - [ListModelBiasJobDefinitionsRequestRequestTypeDef](#listmodelbiasjobdefinitionsrequestrequesttypedef)
  - [ListModelBiasJobDefinitionsResponseTypeDef](#listmodelbiasjobdefinitionsresponsetypedef)
  - [ListModelExplainabilityJobDefinitionsRequestRequestTypeDef](#listmodelexplainabilityjobdefinitionsrequestrequesttypedef)
  - [ListModelExplainabilityJobDefinitionsResponseTypeDef](#listmodelexplainabilityjobdefinitionsresponsetypedef)
  - [ListModelMetadataRequestRequestTypeDef](#listmodelmetadatarequestrequesttypedef)
  - [ListModelMetadataResponseTypeDef](#listmodelmetadataresponsetypedef)
  - [ListModelPackageGroupsInputRequestTypeDef](#listmodelpackagegroupsinputrequesttypedef)
  - [ListModelPackageGroupsOutputTypeDef](#listmodelpackagegroupsoutputtypedef)
  - [ListModelPackagesInputRequestTypeDef](#listmodelpackagesinputrequesttypedef)
  - [ListModelPackagesOutputTypeDef](#listmodelpackagesoutputtypedef)
  - [ListModelQualityJobDefinitionsRequestRequestTypeDef](#listmodelqualityjobdefinitionsrequestrequesttypedef)
  - [ListModelQualityJobDefinitionsResponseTypeDef](#listmodelqualityjobdefinitionsresponsetypedef)
  - [ListModelsInputRequestTypeDef](#listmodelsinputrequesttypedef)
  - [ListModelsOutputTypeDef](#listmodelsoutputtypedef)
  - [ListMonitoringExecutionsRequestRequestTypeDef](#listmonitoringexecutionsrequestrequesttypedef)
  - [ListMonitoringExecutionsResponseTypeDef](#listmonitoringexecutionsresponsetypedef)
  - [ListMonitoringSchedulesRequestRequestTypeDef](#listmonitoringschedulesrequestrequesttypedef)
  - [ListMonitoringSchedulesResponseTypeDef](#listmonitoringschedulesresponsetypedef)
  - [ListNotebookInstanceLifecycleConfigsInputRequestTypeDef](#listnotebookinstancelifecycleconfigsinputrequesttypedef)
  - [ListNotebookInstanceLifecycleConfigsOutputTypeDef](#listnotebookinstancelifecycleconfigsoutputtypedef)
  - [ListNotebookInstancesInputRequestTypeDef](#listnotebookinstancesinputrequesttypedef)
  - [ListNotebookInstancesOutputTypeDef](#listnotebookinstancesoutputtypedef)
  - [ListPipelineExecutionStepsRequestRequestTypeDef](#listpipelineexecutionstepsrequestrequesttypedef)
  - [ListPipelineExecutionStepsResponseTypeDef](#listpipelineexecutionstepsresponsetypedef)
  - [ListPipelineExecutionsRequestRequestTypeDef](#listpipelineexecutionsrequestrequesttypedef)
  - [ListPipelineExecutionsResponseTypeDef](#listpipelineexecutionsresponsetypedef)
  - [ListPipelineParametersForExecutionRequestRequestTypeDef](#listpipelineparametersforexecutionrequestrequesttypedef)
  - [ListPipelineParametersForExecutionResponseTypeDef](#listpipelineparametersforexecutionresponsetypedef)
  - [ListPipelinesRequestRequestTypeDef](#listpipelinesrequestrequesttypedef)
  - [ListPipelinesResponseTypeDef](#listpipelinesresponsetypedef)
  - [ListProcessingJobsRequestRequestTypeDef](#listprocessingjobsrequestrequesttypedef)
  - [ListProcessingJobsResponseTypeDef](#listprocessingjobsresponsetypedef)
  - [ListProjectsInputRequestTypeDef](#listprojectsinputrequesttypedef)
  - [ListProjectsOutputTypeDef](#listprojectsoutputtypedef)
  - [ListStudioLifecycleConfigsRequestRequestTypeDef](#liststudiolifecycleconfigsrequestrequesttypedef)
  - [ListStudioLifecycleConfigsResponseTypeDef](#liststudiolifecycleconfigsresponsetypedef)
  - [ListSubscribedWorkteamsRequestRequestTypeDef](#listsubscribedworkteamsrequestrequesttypedef)
  - [ListSubscribedWorkteamsResponseTypeDef](#listsubscribedworkteamsresponsetypedef)
  - [ListTagsInputRequestTypeDef](#listtagsinputrequesttypedef)
  - [ListTagsOutputTypeDef](#listtagsoutputtypedef)
  - [ListTrainingJobsForHyperParameterTuningJobRequestRequestTypeDef](#listtrainingjobsforhyperparametertuningjobrequestrequesttypedef)
  - [ListTrainingJobsForHyperParameterTuningJobResponseTypeDef](#listtrainingjobsforhyperparametertuningjobresponsetypedef)
  - [ListTrainingJobsRequestRequestTypeDef](#listtrainingjobsrequestrequesttypedef)
  - [ListTrainingJobsResponseTypeDef](#listtrainingjobsresponsetypedef)
  - [ListTransformJobsRequestRequestTypeDef](#listtransformjobsrequestrequesttypedef)
  - [ListTransformJobsResponseTypeDef](#listtransformjobsresponsetypedef)
  - [ListTrialComponentsRequestRequestTypeDef](#listtrialcomponentsrequestrequesttypedef)
  - [ListTrialComponentsResponseTypeDef](#listtrialcomponentsresponsetypedef)
  - [ListTrialsRequestRequestTypeDef](#listtrialsrequestrequesttypedef)
  - [ListTrialsResponseTypeDef](#listtrialsresponsetypedef)
  - [ListUserProfilesRequestRequestTypeDef](#listuserprofilesrequestrequesttypedef)
  - [ListUserProfilesResponseTypeDef](#listuserprofilesresponsetypedef)
  - [ListWorkforcesRequestRequestTypeDef](#listworkforcesrequestrequesttypedef)
  - [ListWorkforcesResponseTypeDef](#listworkforcesresponsetypedef)
  - [ListWorkteamsRequestRequestTypeDef](#listworkteamsrequestrequesttypedef)
  - [ListWorkteamsResponseTypeDef](#listworkteamsresponsetypedef)
  - [MemberDefinitionTypeDef](#memberdefinitiontypedef)
  - [MetadataPropertiesTypeDef](#metadatapropertiestypedef)
  - [MetricDataTypeDef](#metricdatatypedef)
  - [MetricDatumTypeDef](#metricdatumtypedef)
  - [MetricDefinitionTypeDef](#metricdefinitiontypedef)
  - [MetricsSourceTypeDef](#metricssourcetypedef)
  - [ModelArtifactsTypeDef](#modelartifactstypedef)
  - [ModelBiasAppSpecificationTypeDef](#modelbiasappspecificationtypedef)
  - [ModelBiasBaselineConfigTypeDef](#modelbiasbaselineconfigtypedef)
  - [ModelBiasJobInputTypeDef](#modelbiasjobinputtypedef)
  - [ModelClientConfigTypeDef](#modelclientconfigtypedef)
  - [ModelConfigurationTypeDef](#modelconfigurationtypedef)
  - [ModelDataQualityTypeDef](#modeldataqualitytypedef)
  - [ModelDeployConfigTypeDef](#modeldeployconfigtypedef)
  - [ModelDeployResultTypeDef](#modeldeployresulttypedef)
  - [ModelDigestsTypeDef](#modeldigeststypedef)
  - [ModelExplainabilityAppSpecificationTypeDef](#modelexplainabilityappspecificationtypedef)
  - [ModelExplainabilityBaselineConfigTypeDef](#modelexplainabilitybaselineconfigtypedef)
  - [ModelExplainabilityJobInputTypeDef](#modelexplainabilityjobinputtypedef)
  - [ModelInputTypeDef](#modelinputtypedef)
  - [ModelLatencyThresholdTypeDef](#modellatencythresholdtypedef)
  - [ModelMetadataFilterTypeDef](#modelmetadatafiltertypedef)
  - [ModelMetadataSearchExpressionTypeDef](#modelmetadatasearchexpressiontypedef)
  - [ModelMetadataSummaryTypeDef](#modelmetadatasummarytypedef)
  - [ModelMetricsTypeDef](#modelmetricstypedef)
  - [ModelPackageContainerDefinitionTypeDef](#modelpackagecontainerdefinitiontypedef)
  - [ModelPackageGroupSummaryTypeDef](#modelpackagegroupsummarytypedef)
  - [ModelPackageGroupTypeDef](#modelpackagegrouptypedef)
  - [ModelPackageStatusDetailsTypeDef](#modelpackagestatusdetailstypedef)
  - [ModelPackageStatusItemTypeDef](#modelpackagestatusitemtypedef)
  - [ModelPackageSummaryTypeDef](#modelpackagesummarytypedef)
  - [ModelPackageTypeDef](#modelpackagetypedef)
  - [ModelPackageValidationProfileTypeDef](#modelpackagevalidationprofiletypedef)
  - [ModelPackageValidationSpecificationTypeDef](#modelpackagevalidationspecificationtypedef)
  - [ModelQualityAppSpecificationTypeDef](#modelqualityappspecificationtypedef)
  - [ModelQualityBaselineConfigTypeDef](#modelqualitybaselineconfigtypedef)
  - [ModelQualityJobInputTypeDef](#modelqualityjobinputtypedef)
  - [ModelQualityTypeDef](#modelqualitytypedef)
  - [ModelStepMetadataTypeDef](#modelstepmetadatatypedef)
  - [ModelSummaryTypeDef](#modelsummarytypedef)
  - [MonitoringAppSpecificationTypeDef](#monitoringappspecificationtypedef)
  - [MonitoringBaselineConfigTypeDef](#monitoringbaselineconfigtypedef)
  - [MonitoringClusterConfigTypeDef](#monitoringclusterconfigtypedef)
  - [MonitoringConstraintsResourceTypeDef](#monitoringconstraintsresourcetypedef)
  - [MonitoringExecutionSummaryTypeDef](#monitoringexecutionsummarytypedef)
  - [MonitoringGroundTruthS3InputTypeDef](#monitoringgroundtruths3inputtypedef)
  - [MonitoringInputTypeDef](#monitoringinputtypedef)
  - [MonitoringJobDefinitionSummaryTypeDef](#monitoringjobdefinitionsummarytypedef)
  - [MonitoringJobDefinitionTypeDef](#monitoringjobdefinitiontypedef)
  - [MonitoringNetworkConfigTypeDef](#monitoringnetworkconfigtypedef)
  - [MonitoringOutputConfigTypeDef](#monitoringoutputconfigtypedef)
  - [MonitoringOutputTypeDef](#monitoringoutputtypedef)
  - [MonitoringResourcesTypeDef](#monitoringresourcestypedef)
  - [MonitoringS3OutputTypeDef](#monitorings3outputtypedef)
  - [MonitoringScheduleConfigTypeDef](#monitoringscheduleconfigtypedef)
  - [MonitoringScheduleSummaryTypeDef](#monitoringschedulesummarytypedef)
  - [MonitoringScheduleTypeDef](#monitoringscheduletypedef)
  - [MonitoringStatisticsResourceTypeDef](#monitoringstatisticsresourcetypedef)
  - [MonitoringStoppingConditionTypeDef](#monitoringstoppingconditiontypedef)
  - [MultiModelConfigTypeDef](#multimodelconfigtypedef)
  - [NeoVpcConfigTypeDef](#neovpcconfigtypedef)
  - [NestedFiltersTypeDef](#nestedfilterstypedef)
  - [NetworkConfigTypeDef](#networkconfigtypedef)
  - [NotebookInstanceLifecycleConfigSummaryTypeDef](#notebookinstancelifecycleconfigsummarytypedef)
  - [NotebookInstanceLifecycleHookTypeDef](#notebookinstancelifecyclehooktypedef)
  - [NotebookInstanceSummaryTypeDef](#notebookinstancesummarytypedef)
  - [NotificationConfigurationTypeDef](#notificationconfigurationtypedef)
  - [ObjectiveStatusCountersTypeDef](#objectivestatuscounterstypedef)
  - [OfflineStoreConfigTypeDef](#offlinestoreconfigtypedef)
  - [OfflineStoreStatusTypeDef](#offlinestorestatustypedef)
  - [OidcConfigForResponseTypeDef](#oidcconfigforresponsetypedef)
  - [OidcConfigTypeDef](#oidcconfigtypedef)
  - [OidcMemberDefinitionTypeDef](#oidcmemberdefinitiontypedef)
  - [OnlineStoreConfigTypeDef](#onlinestoreconfigtypedef)
  - [OnlineStoreSecurityConfigTypeDef](#onlinestoresecurityconfigtypedef)
  - [OutputConfigTypeDef](#outputconfigtypedef)
  - [OutputDataConfigTypeDef](#outputdataconfigtypedef)
  - [OutputParameterTypeDef](#outputparametertypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [ParallelismConfigurationTypeDef](#parallelismconfigurationtypedef)
  - [ParameterRangeTypeDef](#parameterrangetypedef)
  - [ParameterRangesTypeDef](#parameterrangestypedef)
  - [ParameterTypeDef](#parametertypedef)
  - [ParentHyperParameterTuningJobTypeDef](#parenthyperparametertuningjobtypedef)
  - [ParentTypeDef](#parenttypedef)
  - [PendingDeploymentSummaryTypeDef](#pendingdeploymentsummarytypedef)
  - [PendingProductionVariantSummaryTypeDef](#pendingproductionvariantsummarytypedef)
  - [PhaseTypeDef](#phasetypedef)
  - [PipelineDefinitionS3LocationTypeDef](#pipelinedefinitions3locationtypedef)
  - [PipelineExecutionStepMetadataTypeDef](#pipelineexecutionstepmetadatatypedef)
  - [PipelineExecutionStepTypeDef](#pipelineexecutionsteptypedef)
  - [PipelineExecutionSummaryTypeDef](#pipelineexecutionsummarytypedef)
  - [PipelineExecutionTypeDef](#pipelineexecutiontypedef)
  - [PipelineExperimentConfigTypeDef](#pipelineexperimentconfigtypedef)
  - [PipelineSummaryTypeDef](#pipelinesummarytypedef)
  - [PipelineTypeDef](#pipelinetypedef)
  - [ProcessingClusterConfigTypeDef](#processingclusterconfigtypedef)
  - [ProcessingFeatureStoreOutputTypeDef](#processingfeaturestoreoutputtypedef)
  - [ProcessingInputTypeDef](#processinginputtypedef)
  - [ProcessingJobStepMetadataTypeDef](#processingjobstepmetadatatypedef)
  - [ProcessingJobSummaryTypeDef](#processingjobsummarytypedef)
  - [ProcessingJobTypeDef](#processingjobtypedef)
  - [ProcessingOutputConfigTypeDef](#processingoutputconfigtypedef)
  - [ProcessingOutputTypeDef](#processingoutputtypedef)
  - [ProcessingResourcesTypeDef](#processingresourcestypedef)
  - [ProcessingS3InputTypeDef](#processings3inputtypedef)
  - [ProcessingS3OutputTypeDef](#processings3outputtypedef)
  - [ProcessingStoppingConditionTypeDef](#processingstoppingconditiontypedef)
  - [ProductionVariantCoreDumpConfigTypeDef](#productionvariantcoredumpconfigtypedef)
  - [ProductionVariantServerlessConfigTypeDef](#productionvariantserverlessconfigtypedef)
  - [ProductionVariantStatusTypeDef](#productionvariantstatustypedef)
  - [ProductionVariantSummaryTypeDef](#productionvariantsummarytypedef)
  - [ProductionVariantTypeDef](#productionvarianttypedef)
  - [ProfilerConfigForUpdateTypeDef](#profilerconfigforupdatetypedef)
  - [ProfilerConfigTypeDef](#profilerconfigtypedef)
  - [ProfilerRuleConfigurationTypeDef](#profilerruleconfigurationtypedef)
  - [ProfilerRuleEvaluationStatusTypeDef](#profilerruleevaluationstatustypedef)
  - [ProjectSummaryTypeDef](#projectsummarytypedef)
  - [ProjectTypeDef](#projecttypedef)
  - [PropertyNameQueryTypeDef](#propertynamequerytypedef)
  - [PropertyNameSuggestionTypeDef](#propertynamesuggestiontypedef)
  - [ProvisioningParameterTypeDef](#provisioningparametertypedef)
  - [PublicWorkforceTaskPriceTypeDef](#publicworkforcetaskpricetypedef)
  - [PutModelPackageGroupPolicyInputRequestTypeDef](#putmodelpackagegrouppolicyinputrequesttypedef)
  - [PutModelPackageGroupPolicyOutputTypeDef](#putmodelpackagegrouppolicyoutputtypedef)
  - [QualityCheckStepMetadataTypeDef](#qualitycheckstepmetadatatypedef)
  - [QueryFiltersTypeDef](#queryfilterstypedef)
  - [QueryLineageRequestRequestTypeDef](#querylineagerequestrequesttypedef)
  - [QueryLineageResponseTypeDef](#querylineageresponsetypedef)
  - [RStudioServerProAppSettingsTypeDef](#rstudioserverproappsettingstypedef)
  - [RStudioServerProDomainSettingsForUpdateTypeDef](#rstudioserverprodomainsettingsforupdatetypedef)
  - [RStudioServerProDomainSettingsTypeDef](#rstudioserverprodomainsettingstypedef)
  - [RecommendationJobInputConfigTypeDef](#recommendationjobinputconfigtypedef)
  - [RecommendationJobResourceLimitTypeDef](#recommendationjobresourcelimittypedef)
  - [RecommendationJobStoppingConditionsTypeDef](#recommendationjobstoppingconditionstypedef)
  - [RecommendationMetricsTypeDef](#recommendationmetricstypedef)
  - [RedshiftDatasetDefinitionTypeDef](#redshiftdatasetdefinitiontypedef)
  - [RegisterDevicesRequestRequestTypeDef](#registerdevicesrequestrequesttypedef)
  - [RegisterModelStepMetadataTypeDef](#registermodelstepmetadatatypedef)
  - [RenderUiTemplateRequestRequestTypeDef](#renderuitemplaterequestrequesttypedef)
  - [RenderUiTemplateResponseTypeDef](#renderuitemplateresponsetypedef)
  - [RenderableTaskTypeDef](#renderabletasktypedef)
  - [RenderingErrorTypeDef](#renderingerrortypedef)
  - [RepositoryAuthConfigTypeDef](#repositoryauthconfigtypedef)
  - [ResolvedAttributesTypeDef](#resolvedattributestypedef)
  - [ResourceConfigTypeDef](#resourceconfigtypedef)
  - [ResourceLimitsTypeDef](#resourcelimitstypedef)
  - [ResourceSpecTypeDef](#resourcespectypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [RetentionPolicyTypeDef](#retentionpolicytypedef)
  - [RetryPipelineExecutionRequestRequestTypeDef](#retrypipelineexecutionrequestrequesttypedef)
  - [RetryPipelineExecutionResponseTypeDef](#retrypipelineexecutionresponsetypedef)
  - [RetryStrategyTypeDef](#retrystrategytypedef)
  - [S3DataSourceTypeDef](#s3datasourcetypedef)
  - [S3StorageConfigTypeDef](#s3storageconfigtypedef)
  - [ScheduleConfigTypeDef](#scheduleconfigtypedef)
  - [SearchExpressionTypeDef](#searchexpressiontypedef)
  - [SearchRecordTypeDef](#searchrecordtypedef)
  - [SearchRequestRequestTypeDef](#searchrequestrequesttypedef)
  - [SearchResponseTypeDef](#searchresponsetypedef)
  - [SecondaryStatusTransitionTypeDef](#secondarystatustransitiontypedef)
  - [SendPipelineExecutionStepFailureRequestRequestTypeDef](#sendpipelineexecutionstepfailurerequestrequesttypedef)
  - [SendPipelineExecutionStepFailureResponseTypeDef](#sendpipelineexecutionstepfailureresponsetypedef)
  - [SendPipelineExecutionStepSuccessRequestRequestTypeDef](#sendpipelineexecutionstepsuccessrequestrequesttypedef)
  - [SendPipelineExecutionStepSuccessResponseTypeDef](#sendpipelineexecutionstepsuccessresponsetypedef)
  - [ServiceCatalogProvisionedProductDetailsTypeDef](#servicecatalogprovisionedproductdetailstypedef)
  - [ServiceCatalogProvisioningDetailsTypeDef](#servicecatalogprovisioningdetailstypedef)
  - [ServiceCatalogProvisioningUpdateDetailsTypeDef](#servicecatalogprovisioningupdatedetailstypedef)
  - [SharingSettingsTypeDef](#sharingsettingstypedef)
  - [ShuffleConfigTypeDef](#shuffleconfigtypedef)
  - [SourceAlgorithmSpecificationTypeDef](#sourcealgorithmspecificationtypedef)
  - [SourceAlgorithmTypeDef](#sourcealgorithmtypedef)
  - [SourceIpConfigTypeDef](#sourceipconfigtypedef)
  - [StartMonitoringScheduleRequestRequestTypeDef](#startmonitoringschedulerequestrequesttypedef)
  - [StartNotebookInstanceInputRequestTypeDef](#startnotebookinstanceinputrequesttypedef)
  - [StartPipelineExecutionRequestRequestTypeDef](#startpipelineexecutionrequestrequesttypedef)
  - [StartPipelineExecutionResponseTypeDef](#startpipelineexecutionresponsetypedef)
  - [StopAutoMLJobRequestRequestTypeDef](#stopautomljobrequestrequesttypedef)
  - [StopCompilationJobRequestRequestTypeDef](#stopcompilationjobrequestrequesttypedef)
  - [StopEdgePackagingJobRequestRequestTypeDef](#stopedgepackagingjobrequestrequesttypedef)
  - [StopHyperParameterTuningJobRequestRequestTypeDef](#stophyperparametertuningjobrequestrequesttypedef)
  - [StopInferenceRecommendationsJobRequestRequestTypeDef](#stopinferencerecommendationsjobrequestrequesttypedef)
  - [StopLabelingJobRequestRequestTypeDef](#stoplabelingjobrequestrequesttypedef)
  - [StopMonitoringScheduleRequestRequestTypeDef](#stopmonitoringschedulerequestrequesttypedef)
  - [StopNotebookInstanceInputRequestTypeDef](#stopnotebookinstanceinputrequesttypedef)
  - [StopPipelineExecutionRequestRequestTypeDef](#stoppipelineexecutionrequestrequesttypedef)
  - [StopPipelineExecutionResponseTypeDef](#stoppipelineexecutionresponsetypedef)
  - [StopProcessingJobRequestRequestTypeDef](#stopprocessingjobrequestrequesttypedef)
  - [StopTrainingJobRequestRequestTypeDef](#stoptrainingjobrequestrequesttypedef)
  - [StopTransformJobRequestRequestTypeDef](#stoptransformjobrequestrequesttypedef)
  - [StoppingConditionTypeDef](#stoppingconditiontypedef)
  - [StudioLifecycleConfigDetailsTypeDef](#studiolifecycleconfigdetailstypedef)
  - [SubscribedWorkteamTypeDef](#subscribedworkteamtypedef)
  - [SuggestionQueryTypeDef](#suggestionquerytypedef)
  - [TagTypeDef](#tagtypedef)
  - [TargetPlatformTypeDef](#targetplatformtypedef)
  - [TensorBoardAppSettingsTypeDef](#tensorboardappsettingstypedef)
  - [TensorBoardOutputConfigTypeDef](#tensorboardoutputconfigtypedef)
  - [TrafficPatternTypeDef](#trafficpatterntypedef)
  - [TrafficRoutingConfigTypeDef](#trafficroutingconfigtypedef)
  - [TrainingJobDefinitionTypeDef](#trainingjobdefinitiontypedef)
  - [TrainingJobStatusCountersTypeDef](#trainingjobstatuscounterstypedef)
  - [TrainingJobStepMetadataTypeDef](#trainingjobstepmetadatatypedef)
  - [TrainingJobSummaryTypeDef](#trainingjobsummarytypedef)
  - [TrainingJobTypeDef](#trainingjobtypedef)
  - [TrainingSpecificationTypeDef](#trainingspecificationtypedef)
  - [TransformDataSourceTypeDef](#transformdatasourcetypedef)
  - [TransformInputTypeDef](#transforminputtypedef)
  - [TransformJobDefinitionTypeDef](#transformjobdefinitiontypedef)
  - [TransformJobStepMetadataTypeDef](#transformjobstepmetadatatypedef)
  - [TransformJobSummaryTypeDef](#transformjobsummarytypedef)
  - [TransformJobTypeDef](#transformjobtypedef)
  - [TransformOutputTypeDef](#transformoutputtypedef)
  - [TransformResourcesTypeDef](#transformresourcestypedef)
  - [TransformS3DataSourceTypeDef](#transforms3datasourcetypedef)
  - [TrialComponentArtifactTypeDef](#trialcomponentartifacttypedef)
  - [TrialComponentMetricSummaryTypeDef](#trialcomponentmetricsummarytypedef)
  - [TrialComponentParameterValueTypeDef](#trialcomponentparametervaluetypedef)
  - [TrialComponentSimpleSummaryTypeDef](#trialcomponentsimplesummarytypedef)
  - [TrialComponentSourceDetailTypeDef](#trialcomponentsourcedetailtypedef)
  - [TrialComponentSourceTypeDef](#trialcomponentsourcetypedef)
  - [TrialComponentStatusTypeDef](#trialcomponentstatustypedef)
  - [TrialComponentSummaryTypeDef](#trialcomponentsummarytypedef)
  - [TrialComponentTypeDef](#trialcomponenttypedef)
  - [TrialSourceTypeDef](#trialsourcetypedef)
  - [TrialSummaryTypeDef](#trialsummarytypedef)
  - [TrialTypeDef](#trialtypedef)
  - [TuningJobCompletionCriteriaTypeDef](#tuningjobcompletioncriteriatypedef)
  - [TuningJobStepMetaDataTypeDef](#tuningjobstepmetadatatypedef)
  - [USDTypeDef](#usdtypedef)
  - [UiConfigTypeDef](#uiconfigtypedef)
  - [UiTemplateInfoTypeDef](#uitemplateinfotypedef)
  - [UiTemplateTypeDef](#uitemplatetypedef)
  - [UpdateActionRequestRequestTypeDef](#updateactionrequestrequesttypedef)
  - [UpdateActionResponseTypeDef](#updateactionresponsetypedef)
  - [UpdateAppImageConfigRequestRequestTypeDef](#updateappimageconfigrequestrequesttypedef)
  - [UpdateAppImageConfigResponseTypeDef](#updateappimageconfigresponsetypedef)
  - [UpdateArtifactRequestRequestTypeDef](#updateartifactrequestrequesttypedef)
  - [UpdateArtifactResponseTypeDef](#updateartifactresponsetypedef)
  - [UpdateCodeRepositoryInputRequestTypeDef](#updatecoderepositoryinputrequesttypedef)
  - [UpdateCodeRepositoryOutputTypeDef](#updatecoderepositoryoutputtypedef)
  - [UpdateContextRequestRequestTypeDef](#updatecontextrequestrequesttypedef)
  - [UpdateContextResponseTypeDef](#updatecontextresponsetypedef)
  - [UpdateDeviceFleetRequestRequestTypeDef](#updatedevicefleetrequestrequesttypedef)
  - [UpdateDevicesRequestRequestTypeDef](#updatedevicesrequestrequesttypedef)
  - [UpdateDomainRequestRequestTypeDef](#updatedomainrequestrequesttypedef)
  - [UpdateDomainResponseTypeDef](#updatedomainresponsetypedef)
  - [UpdateEndpointInputRequestTypeDef](#updateendpointinputrequesttypedef)
  - [UpdateEndpointOutputTypeDef](#updateendpointoutputtypedef)
  - [UpdateEndpointWeightsAndCapacitiesInputRequestTypeDef](#updateendpointweightsandcapacitiesinputrequesttypedef)
  - [UpdateEndpointWeightsAndCapacitiesOutputTypeDef](#updateendpointweightsandcapacitiesoutputtypedef)
  - [UpdateExperimentRequestRequestTypeDef](#updateexperimentrequestrequesttypedef)
  - [UpdateExperimentResponseTypeDef](#updateexperimentresponsetypedef)
  - [UpdateImageRequestRequestTypeDef](#updateimagerequestrequesttypedef)
  - [UpdateImageResponseTypeDef](#updateimageresponsetypedef)
  - [UpdateModelPackageInputRequestTypeDef](#updatemodelpackageinputrequesttypedef)
  - [UpdateModelPackageOutputTypeDef](#updatemodelpackageoutputtypedef)
  - [UpdateMonitoringScheduleRequestRequestTypeDef](#updatemonitoringschedulerequestrequesttypedef)
  - [UpdateMonitoringScheduleResponseTypeDef](#updatemonitoringscheduleresponsetypedef)
  - [UpdateNotebookInstanceInputRequestTypeDef](#updatenotebookinstanceinputrequesttypedef)
  - [UpdateNotebookInstanceLifecycleConfigInputRequestTypeDef](#updatenotebookinstancelifecycleconfiginputrequesttypedef)
  - [UpdatePipelineExecutionRequestRequestTypeDef](#updatepipelineexecutionrequestrequesttypedef)
  - [UpdatePipelineExecutionResponseTypeDef](#updatepipelineexecutionresponsetypedef)
  - [UpdatePipelineRequestRequestTypeDef](#updatepipelinerequestrequesttypedef)
  - [UpdatePipelineResponseTypeDef](#updatepipelineresponsetypedef)
  - [UpdateProjectInputRequestTypeDef](#updateprojectinputrequesttypedef)
  - [UpdateProjectOutputTypeDef](#updateprojectoutputtypedef)
  - [UpdateTrainingJobRequestRequestTypeDef](#updatetrainingjobrequestrequesttypedef)
  - [UpdateTrainingJobResponseTypeDef](#updatetrainingjobresponsetypedef)
  - [UpdateTrialComponentRequestRequestTypeDef](#updatetrialcomponentrequestrequesttypedef)
  - [UpdateTrialComponentResponseTypeDef](#updatetrialcomponentresponsetypedef)
  - [UpdateTrialRequestRequestTypeDef](#updatetrialrequestrequesttypedef)
  - [UpdateTrialResponseTypeDef](#updatetrialresponsetypedef)
  - [UpdateUserProfileRequestRequestTypeDef](#updateuserprofilerequestrequesttypedef)
  - [UpdateUserProfileResponseTypeDef](#updateuserprofileresponsetypedef)
  - [UpdateWorkforceRequestRequestTypeDef](#updateworkforcerequestrequesttypedef)
  - [UpdateWorkforceResponseTypeDef](#updateworkforceresponsetypedef)
  - [UpdateWorkteamRequestRequestTypeDef](#updateworkteamrequestrequesttypedef)
  - [UpdateWorkteamResponseTypeDef](#updateworkteamresponsetypedef)
  - [UserContextTypeDef](#usercontexttypedef)
  - [UserProfileDetailsTypeDef](#userprofiledetailstypedef)
  - [UserSettingsTypeDef](#usersettingstypedef)
  - [VariantPropertyTypeDef](#variantpropertytypedef)
  - [VertexTypeDef](#vertextypedef)
  - [VpcConfigTypeDef](#vpcconfigtypedef)
  - [WaiterConfigTypeDef](#waiterconfigtypedef)
  - [WorkforceTypeDef](#workforcetypedef)
  - [WorkteamTypeDef](#workteamtypedef)

<a id="actionsourcetypedef"></a>

## ActionSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ActionSourceTypeDef
```

Required fields:

- `SourceUri`: `str`

Optional fields:

- `SourceType`: `str`
- `SourceId`: `str`

<a id="actionsummarytypedef"></a>

## ActionSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ActionSummaryTypeDef
```

Optional fields:

- `ActionArn`: `str`
- `ActionName`: `str`
- `Source`: [ActionSourceTypeDef](./type_defs.md#actionsourcetypedef)
- `ActionType`: `str`
- `Status`: [ActionStatusType](./literals.md#actionstatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="addassociationrequestrequesttypedef"></a>

## AddAssociationRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AddAssociationRequestRequestTypeDef
```

Required fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`

Optional fields:

- `AssociationType`:
  [AssociationEdgeTypeType](./literals.md#associationedgetypetype)

<a id="addassociationresponsetypedef"></a>

## AddAssociationResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AddAssociationResponseTypeDef
```

Required fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="addtagsinputrequesttypedef"></a>

## AddTagsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AddTagsInputRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="addtagsoutputtypedef"></a>

## AddTagsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AddTagsOutputTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="additionalinferencespecificationdefinitiontypedef"></a>

## AdditionalInferenceSpecificationDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AdditionalInferenceSpecificationDefinitionTypeDef
```

Required fields:

- `Name`: `str`
- `Containers`:
  `Sequence`\[[ModelPackageContainerDefinitionTypeDef](./type_defs.md#modelpackagecontainerdefinitiontypedef)\]

Optional fields:

- `Description`: `str`
- `SupportedTransformInstanceTypes`:
  `Sequence`\[[TransformInstanceTypeType](./literals.md#transforminstancetypetype)\]
- `SupportedRealtimeInferenceInstanceTypes`:
  `Sequence`\[[ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)\]
- `SupportedContentTypes`: `Sequence`\[`str`\]
- `SupportedResponseMIMETypes`: `Sequence`\[`str`\]

<a id="agentversiontypedef"></a>

## AgentVersionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AgentVersionTypeDef
```

Required fields:

- `Version`: `str`
- `AgentCount`: `int`

<a id="alarmtypedef"></a>

## AlarmTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlarmTypeDef
```

Optional fields:

- `AlarmName`: `str`

<a id="algorithmspecificationtypedef"></a>

## AlgorithmSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmSpecificationTypeDef
```

Required fields:

- `TrainingInputMode`:
  [TrainingInputModeType](./literals.md#traininginputmodetype)

Optional fields:

- `TrainingImage`: `str`
- `AlgorithmName`: `str`
- `MetricDefinitions`:
  `Sequence`\[[MetricDefinitionTypeDef](./type_defs.md#metricdefinitiontypedef)\]
- `EnableSageMakerMetricsTimeSeries`: `bool`

<a id="algorithmstatusdetailstypedef"></a>

## AlgorithmStatusDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmStatusDetailsTypeDef
```

Optional fields:

- `ValidationStatuses`:
  `List`\[[AlgorithmStatusItemTypeDef](./type_defs.md#algorithmstatusitemtypedef)\]
- `ImageScanStatuses`:
  `List`\[[AlgorithmStatusItemTypeDef](./type_defs.md#algorithmstatusitemtypedef)\]

<a id="algorithmstatusitemtypedef"></a>

## AlgorithmStatusItemTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmStatusItemTypeDef
```

Required fields:

- `Name`: `str`
- `Status`:
  [DetailedAlgorithmStatusType](./literals.md#detailedalgorithmstatustype)

Optional fields:

- `FailureReason`: `str`

<a id="algorithmsummarytypedef"></a>

## AlgorithmSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmSummaryTypeDef
```

Required fields:

- `AlgorithmName`: `str`
- `AlgorithmArn`: `str`
- `CreationTime`: `datetime`
- `AlgorithmStatus`: [AlgorithmStatusType](./literals.md#algorithmstatustype)

Optional fields:

- `AlgorithmDescription`: `str`

<a id="algorithmvalidationprofiletypedef"></a>

## AlgorithmValidationProfileTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmValidationProfileTypeDef
```

Required fields:

- `ProfileName`: `str`
- `TrainingJobDefinition`:
  [TrainingJobDefinitionTypeDef](./type_defs.md#trainingjobdefinitiontypedef)

Optional fields:

- `TransformJobDefinition`:
  [TransformJobDefinitionTypeDef](./type_defs.md#transformjobdefinitiontypedef)

<a id="algorithmvalidationspecificationtypedef"></a>

## AlgorithmValidationSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AlgorithmValidationSpecificationTypeDef
```

Required fields:

- `ValidationRole`: `str`
- `ValidationProfiles`:
  `Sequence`\[[AlgorithmValidationProfileTypeDef](./type_defs.md#algorithmvalidationprofiletypedef)\]

<a id="annotationconsolidationconfigtypedef"></a>

## AnnotationConsolidationConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AnnotationConsolidationConfigTypeDef
```

Required fields:

- `AnnotationConsolidationLambdaArn`: `str`

<a id="appdetailstypedef"></a>

## AppDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AppDetailsTypeDef
```

Optional fields:

- `DomainId`: `str`
- `UserProfileName`: `str`
- `AppType`: [AppTypeType](./literals.md#apptypetype)
- `AppName`: `str`
- `Status`: [AppStatusType](./literals.md#appstatustype)
- `CreationTime`: `datetime`

<a id="appimageconfigdetailstypedef"></a>

## AppImageConfigDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AppImageConfigDetailsTypeDef
```

Optional fields:

- `AppImageConfigArn`: `str`
- `AppImageConfigName`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `KernelGatewayImageConfig`:
  [KernelGatewayImageConfigTypeDef](./type_defs.md#kernelgatewayimageconfigtypedef)

<a id="appspecificationtypedef"></a>

## AppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`

Optional fields:

- `ContainerEntrypoint`: `Sequence`\[`str`\]
- `ContainerArguments`: `Sequence`\[`str`\]

<a id="artifactsourcetypedef"></a>

## ArtifactSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ArtifactSourceTypeDef
```

Required fields:

- `SourceUri`: `str`

Optional fields:

- `SourceTypes`:
  `Sequence`\[[ArtifactSourceTypeTypeDef](./type_defs.md#artifactsourcetypetypedef)\]

<a id="artifactsourcetypetypedef"></a>

## ArtifactSourceTypeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ArtifactSourceTypeTypeDef
```

Required fields:

- `SourceIdType`:
  [ArtifactSourceIdTypeType](./literals.md#artifactsourceidtypetype)
- `Value`: `str`

<a id="artifactsummarytypedef"></a>

## ArtifactSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ArtifactSummaryTypeDef
```

Optional fields:

- `ArtifactArn`: `str`
- `ArtifactName`: `str`
- `Source`: [ArtifactSourceTypeDef](./type_defs.md#artifactsourcetypedef)
- `ArtifactType`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="associatetrialcomponentrequestrequesttypedef"></a>

## AssociateTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AssociateTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`
- `TrialName`: `str`

<a id="associatetrialcomponentresponsetypedef"></a>

## AssociateTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AssociateTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentArn`: `str`
- `TrialArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="associationsummarytypedef"></a>

## AssociationSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AssociationSummaryTypeDef
```

Optional fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`
- `SourceType`: `str`
- `DestinationType`: `str`
- `AssociationType`:
  [AssociationEdgeTypeType](./literals.md#associationedgetypetype)
- `SourceName`: `str`
- `DestinationName`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)

<a id="asyncinferenceclientconfigtypedef"></a>

## AsyncInferenceClientConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AsyncInferenceClientConfigTypeDef
```

Optional fields:

- `MaxConcurrentInvocationsPerInstance`: `int`

<a id="asyncinferenceconfigtypedef"></a>

## AsyncInferenceConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AsyncInferenceConfigTypeDef
```

Required fields:

- `OutputConfig`:
  [AsyncInferenceOutputConfigTypeDef](./type_defs.md#asyncinferenceoutputconfigtypedef)

Optional fields:

- `ClientConfig`:
  [AsyncInferenceClientConfigTypeDef](./type_defs.md#asyncinferenceclientconfigtypedef)

<a id="asyncinferencenotificationconfigtypedef"></a>

## AsyncInferenceNotificationConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AsyncInferenceNotificationConfigTypeDef
```

Optional fields:

- `SuccessTopic`: `str`
- `ErrorTopic`: `str`

<a id="asyncinferenceoutputconfigtypedef"></a>

## AsyncInferenceOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AsyncInferenceOutputConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `KmsKeyId`: `str`
- `NotificationConfig`:
  [AsyncInferenceNotificationConfigTypeDef](./type_defs.md#asyncinferencenotificationconfigtypedef)

<a id="athenadatasetdefinitiontypedef"></a>

## AthenaDatasetDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AthenaDatasetDefinitionTypeDef
```

Required fields:

- `Catalog`: `str`
- `Database`: `str`
- `QueryString`: `str`
- `OutputS3Uri`: `str`
- `OutputFormat`:
  [AthenaResultFormatType](./literals.md#athenaresultformattype)

Optional fields:

- `WorkGroup`: `str`
- `KmsKeyId`: `str`
- `OutputCompression`:
  [AthenaResultCompressionTypeType](./literals.md#athenaresultcompressiontypetype)

<a id="automlcandidatesteptypedef"></a>

## AutoMLCandidateStepTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLCandidateStepTypeDef
```

Required fields:

- `CandidateStepType`:
  [CandidateStepTypeType](./literals.md#candidatesteptypetype)
- `CandidateStepArn`: `str`
- `CandidateStepName`: `str`

<a id="automlcandidatetypedef"></a>

## AutoMLCandidateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLCandidateTypeDef
```

Required fields:

- `CandidateName`: `str`
- `ObjectiveStatus`: [ObjectiveStatusType](./literals.md#objectivestatustype)
- `CandidateSteps`:
  `List`\[[AutoMLCandidateStepTypeDef](./type_defs.md#automlcandidatesteptypedef)\]
- `CandidateStatus`: [CandidateStatusType](./literals.md#candidatestatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

Optional fields:

- `FinalAutoMLJobObjectiveMetric`:
  [FinalAutoMLJobObjectiveMetricTypeDef](./type_defs.md#finalautomljobobjectivemetrictypedef)
- `InferenceContainers`:
  `List`\[[AutoMLContainerDefinitionTypeDef](./type_defs.md#automlcontainerdefinitiontypedef)\]
- `EndTime`: `datetime`
- `FailureReason`: `str`
- `CandidateProperties`:
  [CandidatePropertiesTypeDef](./type_defs.md#candidatepropertiestypedef)

<a id="automlchanneltypedef"></a>

## AutoMLChannelTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLChannelTypeDef
```

Required fields:

- `DataSource`:
  [AutoMLDataSourceTypeDef](./type_defs.md#automldatasourcetypedef)
- `TargetAttributeName`: `str`

Optional fields:

- `CompressionType`: [CompressionTypeType](./literals.md#compressiontypetype)
- `ContentType`: `str`

<a id="automlcontainerdefinitiontypedef"></a>

## AutoMLContainerDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLContainerDefinitionTypeDef
```

Required fields:

- `Image`: `str`
- `ModelDataUrl`: `str`

Optional fields:

- `Environment`: `Dict`\[`str`, `str`\]

<a id="automldatasourcetypedef"></a>

## AutoMLDataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLDataSourceTypeDef
```

Required fields:

- `S3DataSource`:
  [AutoMLS3DataSourceTypeDef](./type_defs.md#automls3datasourcetypedef)

<a id="automljobartifactstypedef"></a>

## AutoMLJobArtifactsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLJobArtifactsTypeDef
```

Optional fields:

- `CandidateDefinitionNotebookLocation`: `str`
- `DataExplorationNotebookLocation`: `str`

<a id="automljobcompletioncriteriatypedef"></a>

## AutoMLJobCompletionCriteriaTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLJobCompletionCriteriaTypeDef
```

Optional fields:

- `MaxCandidates`: `int`
- `MaxRuntimePerTrainingJobInSeconds`: `int`
- `MaxAutoMLJobRuntimeInSeconds`: `int`

<a id="automljobconfigtypedef"></a>

## AutoMLJobConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLJobConfigTypeDef
```

Optional fields:

- `CompletionCriteria`:
  [AutoMLJobCompletionCriteriaTypeDef](./type_defs.md#automljobcompletioncriteriatypedef)
- `SecurityConfig`:
  [AutoMLSecurityConfigTypeDef](./type_defs.md#automlsecurityconfigtypedef)

<a id="automljobobjectivetypedef"></a>

## AutoMLJobObjectiveTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLJobObjectiveTypeDef
```

Required fields:

- `MetricName`: [AutoMLMetricEnumType](./literals.md#automlmetricenumtype)

<a id="automljobsummarytypedef"></a>

## AutoMLJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLJobSummaryTypeDef
```

Required fields:

- `AutoMLJobName`: `str`
- `AutoMLJobArn`: `str`
- `AutoMLJobStatus`: [AutoMLJobStatusType](./literals.md#automljobstatustype)
- `AutoMLJobSecondaryStatus`:
  [AutoMLJobSecondaryStatusType](./literals.md#automljobsecondarystatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

Optional fields:

- `EndTime`: `datetime`
- `FailureReason`: `str`
- `PartialFailureReasons`:
  `List`\[[AutoMLPartialFailureReasonTypeDef](./type_defs.md#automlpartialfailurereasontypedef)\]

<a id="automloutputdataconfigtypedef"></a>

## AutoMLOutputDataConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLOutputDataConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `KmsKeyId`: `str`

<a id="automlpartialfailurereasontypedef"></a>

## AutoMLPartialFailureReasonTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLPartialFailureReasonTypeDef
```

Optional fields:

- `PartialFailureMessage`: `str`

<a id="automls3datasourcetypedef"></a>

## AutoMLS3DataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLS3DataSourceTypeDef
```

Required fields:

- `S3DataType`: [AutoMLS3DataTypeType](./literals.md#automls3datatypetype)
- `S3Uri`: `str`

<a id="automlsecurityconfigtypedef"></a>

## AutoMLSecurityConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoMLSecurityConfigTypeDef
```

Optional fields:

- `VolumeKmsKeyId`: `str`
- `EnableInterContainerTrafficEncryption`: `bool`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)

<a id="autorollbackconfigtypedef"></a>

## AutoRollbackConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import AutoRollbackConfigTypeDef
```

Optional fields:

- `Alarms`: `Sequence`\[[AlarmTypeDef](./type_defs.md#alarmtypedef)\]

<a id="batchdescribemodelpackageerrortypedef"></a>

## BatchDescribeModelPackageErrorTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BatchDescribeModelPackageErrorTypeDef
```

Required fields:

- `ErrorCode`: `str`
- `ErrorResponse`: `str`

<a id="batchdescribemodelpackageinputrequesttypedef"></a>

## BatchDescribeModelPackageInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BatchDescribeModelPackageInputRequestTypeDef
```

Required fields:

- `ModelPackageArnList`: `Sequence`\[`str`\]

<a id="batchdescribemodelpackageoutputtypedef"></a>

## BatchDescribeModelPackageOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BatchDescribeModelPackageOutputTypeDef
```

Required fields:

- `ModelPackageSummaries`: `Dict`\[`str`,
  [BatchDescribeModelPackageSummaryTypeDef](./type_defs.md#batchdescribemodelpackagesummarytypedef)\]
- `BatchDescribeModelPackageErrorMap`: `Dict`\[`str`,
  [BatchDescribeModelPackageErrorTypeDef](./type_defs.md#batchdescribemodelpackageerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="batchdescribemodelpackagesummarytypedef"></a>

## BatchDescribeModelPackageSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BatchDescribeModelPackageSummaryTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`
- `ModelPackageArn`: `str`
- `CreationTime`: `datetime`
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `ModelPackageStatus`:
  [ModelPackageStatusType](./literals.md#modelpackagestatustype)

Optional fields:

- `ModelPackageVersion`: `int`
- `ModelPackageDescription`: `str`
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)

<a id="biastypedef"></a>

## BiasTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BiasTypeDef
```

Optional fields:

- `Report`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `PreTrainingReport`:
  [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `PostTrainingReport`:
  [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="bluegreenupdatepolicytypedef"></a>

## BlueGreenUpdatePolicyTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import BlueGreenUpdatePolicyTypeDef
```

Required fields:

- `TrafficRoutingConfiguration`:
  [TrafficRoutingConfigTypeDef](./type_defs.md#trafficroutingconfigtypedef)

Optional fields:

- `TerminationWaitInSeconds`: `int`
- `MaximumExecutionTimeoutInSeconds`: `int`

<a id="cachehitresulttypedef"></a>

## CacheHitResultTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CacheHitResultTypeDef
```

Optional fields:

- `SourcePipelineExecutionArn`: `str`

<a id="callbackstepmetadatatypedef"></a>

## CallbackStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CallbackStepMetadataTypeDef
```

Optional fields:

- `CallbackToken`: `str`
- `SqsQueueUrl`: `str`
- `OutputParameters`:
  `List`\[[OutputParameterTypeDef](./type_defs.md#outputparametertypedef)\]

<a id="candidateartifactlocationstypedef"></a>

## CandidateArtifactLocationsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CandidateArtifactLocationsTypeDef
```

Required fields:

- `Explainability`: `str`

Optional fields:

- `ModelInsights`: `str`

<a id="candidatepropertiestypedef"></a>

## CandidatePropertiesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CandidatePropertiesTypeDef
```

Optional fields:

- `CandidateArtifactLocations`:
  [CandidateArtifactLocationsTypeDef](./type_defs.md#candidateartifactlocationstypedef)
- `CandidateMetrics`:
  `List`\[[MetricDatumTypeDef](./type_defs.md#metricdatumtypedef)\]

<a id="capacitysizetypedef"></a>

## CapacitySizeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CapacitySizeTypeDef
```

Required fields:

- `Type`: [CapacitySizeTypeType](./literals.md#capacitysizetypetype)
- `Value`: `int`

<a id="capturecontenttypeheadertypedef"></a>

## CaptureContentTypeHeaderTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CaptureContentTypeHeaderTypeDef
```

Optional fields:

- `CsvContentTypes`: `Sequence`\[`str`\]
- `JsonContentTypes`: `Sequence`\[`str`\]

<a id="captureoptiontypedef"></a>

## CaptureOptionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CaptureOptionTypeDef
```

Required fields:

- `CaptureMode`: [CaptureModeType](./literals.md#capturemodetype)

<a id="categoricalparameterrangespecificationtypedef"></a>

## CategoricalParameterRangeSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CategoricalParameterRangeSpecificationTypeDef
```

Required fields:

- `Values`: `Sequence`\[`str`\]

<a id="categoricalparameterrangetypedef"></a>

## CategoricalParameterRangeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CategoricalParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `Values`: `Sequence`\[`str`\]

<a id="categoricalparametertypedef"></a>

## CategoricalParameterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CategoricalParameterTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `Sequence`\[`str`\]

<a id="channelspecificationtypedef"></a>

## ChannelSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ChannelSpecificationTypeDef
```

Required fields:

- `Name`: `str`
- `SupportedContentTypes`: `Sequence`\[`str`\]
- `SupportedInputModes`:
  `Sequence`\[[TrainingInputModeType](./literals.md#traininginputmodetype)\]

Optional fields:

- `Description`: `str`
- `IsRequired`: `bool`
- `SupportedCompressionTypes`:
  `Sequence`\[[CompressionTypeType](./literals.md#compressiontypetype)\]

<a id="channeltypedef"></a>

## ChannelTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ChannelTypeDef
```

Required fields:

- `ChannelName`: `str`
- `DataSource`: [DataSourceTypeDef](./type_defs.md#datasourcetypedef)

Optional fields:

- `ContentType`: `str`
- `CompressionType`: [CompressionTypeType](./literals.md#compressiontypetype)
- `RecordWrapperType`: [RecordWrapperType](./literals.md#recordwrappertype)
- `InputMode`: [TrainingInputModeType](./literals.md#traininginputmodetype)
- `ShuffleConfig`: [ShuffleConfigTypeDef](./type_defs.md#shuffleconfigtypedef)

<a id="checkpointconfigtypedef"></a>

## CheckpointConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CheckpointConfigTypeDef
```

Required fields:

- `S3Uri`: `str`

Optional fields:

- `LocalPath`: `str`

<a id="clarifycheckstepmetadatatypedef"></a>

## ClarifyCheckStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ClarifyCheckStepMetadataTypeDef
```

Optional fields:

- `CheckType`: `str`
- `BaselineUsedForDriftCheckConstraints`: `str`
- `CalculatedBaselineConstraints`: `str`
- `ModelPackageGroupName`: `str`
- `ViolationReport`: `str`
- `CheckJobArn`: `str`
- `SkipCheck`: `bool`
- `RegisterNewBaseline`: `bool`

<a id="coderepositorysummarytypedef"></a>

## CodeRepositorySummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CodeRepositorySummaryTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`
- `CodeRepositoryArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

Optional fields:

- `GitConfig`: [GitConfigTypeDef](./type_defs.md#gitconfigtypedef)

<a id="cognitoconfigtypedef"></a>

## CognitoConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CognitoConfigTypeDef
```

Required fields:

- `UserPool`: `str`
- `ClientId`: `str`

<a id="cognitomemberdefinitiontypedef"></a>

## CognitoMemberDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CognitoMemberDefinitionTypeDef
```

Required fields:

- `UserPool`: `str`
- `UserGroup`: `str`
- `ClientId`: `str`

<a id="collectionconfigurationtypedef"></a>

## CollectionConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CollectionConfigurationTypeDef
```

Optional fields:

- `CollectionName`: `str`
- `CollectionParameters`: `Mapping`\[`str`, `str`\]

<a id="compilationjobsummarytypedef"></a>

## CompilationJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CompilationJobSummaryTypeDef
```

Required fields:

- `CompilationJobName`: `str`
- `CompilationJobArn`: `str`
- `CreationTime`: `datetime`
- `CompilationJobStatus`:
  [CompilationJobStatusType](./literals.md#compilationjobstatustype)

Optional fields:

- `CompilationStartTime`: `datetime`
- `CompilationEndTime`: `datetime`
- `CompilationTargetDevice`: [TargetDeviceType](./literals.md#targetdevicetype)
- `CompilationTargetPlatformOs`:
  [TargetPlatformOsType](./literals.md#targetplatformostype)
- `CompilationTargetPlatformArch`:
  [TargetPlatformArchType](./literals.md#targetplatformarchtype)
- `CompilationTargetPlatformAccelerator`:
  [TargetPlatformAcceleratorType](./literals.md#targetplatformacceleratortype)
- `LastModifiedTime`: `datetime`

<a id="conditionstepmetadatatypedef"></a>

## ConditionStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ConditionStepMetadataTypeDef
```

Optional fields:

- `Outcome`: [ConditionOutcomeType](./literals.md#conditionoutcometype)

<a id="containerdefinitiontypedef"></a>

## ContainerDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ContainerDefinitionTypeDef
```

Optional fields:

- `ContainerHostname`: `str`
- `Image`: `str`
- `ImageConfig`: [ImageConfigTypeDef](./type_defs.md#imageconfigtypedef)
- `Mode`: [ContainerModeType](./literals.md#containermodetype)
- `ModelDataUrl`: `str`
- `Environment`: `Mapping`\[`str`, `str`\]
- `ModelPackageName`: `str`
- `InferenceSpecificationName`: `str`
- `MultiModelConfig`:
  [MultiModelConfigTypeDef](./type_defs.md#multimodelconfigtypedef)

<a id="contextsourcetypedef"></a>

## ContextSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ContextSourceTypeDef
```

Required fields:

- `SourceUri`: `str`

Optional fields:

- `SourceType`: `str`
- `SourceId`: `str`

<a id="contextsummarytypedef"></a>

## ContextSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ContextSummaryTypeDef
```

Optional fields:

- `ContextArn`: `str`
- `ContextName`: `str`
- `Source`: [ContextSourceTypeDef](./type_defs.md#contextsourcetypedef)
- `ContextType`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="continuousparameterrangespecificationtypedef"></a>

## ContinuousParameterRangeSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ContinuousParameterRangeSpecificationTypeDef
```

Required fields:

- `MinValue`: `str`
- `MaxValue`: `str`

<a id="continuousparameterrangetypedef"></a>

## ContinuousParameterRangeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ContinuousParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `MinValue`: `str`
- `MaxValue`: `str`

Optional fields:

- `ScalingType`:
  [HyperParameterScalingTypeType](./literals.md#hyperparameterscalingtypetype)

<a id="createactionrequestrequesttypedef"></a>

## CreateActionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateActionRequestRequestTypeDef
```

Required fields:

- `ActionName`: `str`
- `Source`: [ActionSourceTypeDef](./type_defs.md#actionsourcetypedef)
- `ActionType`: `str`

Optional fields:

- `Description`: `str`
- `Status`: [ActionStatusType](./literals.md#actionstatustype)
- `Properties`: `Mapping`\[`str`, `str`\]
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createactionresponsetypedef"></a>

## CreateActionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateActionResponseTypeDef
```

Required fields:

- `ActionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createalgorithminputrequesttypedef"></a>

## CreateAlgorithmInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAlgorithmInputRequestTypeDef
```

Required fields:

- `AlgorithmName`: `str`
- `TrainingSpecification`:
  [TrainingSpecificationTypeDef](./type_defs.md#trainingspecificationtypedef)

Optional fields:

- `AlgorithmDescription`: `str`
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `ValidationSpecification`:
  [AlgorithmValidationSpecificationTypeDef](./type_defs.md#algorithmvalidationspecificationtypedef)
- `CertifyForMarketplace`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createalgorithmoutputtypedef"></a>

## CreateAlgorithmOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAlgorithmOutputTypeDef
```

Required fields:

- `AlgorithmArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createappimageconfigrequestrequesttypedef"></a>

## CreateAppImageConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAppImageConfigRequestRequestTypeDef
```

Required fields:

- `AppImageConfigName`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KernelGatewayImageConfig`:
  [KernelGatewayImageConfigTypeDef](./type_defs.md#kernelgatewayimageconfigtypedef)

<a id="createappimageconfigresponsetypedef"></a>

## CreateAppImageConfigResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAppImageConfigResponseTypeDef
```

Required fields:

- `AppImageConfigArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createapprequestrequesttypedef"></a>

## CreateAppRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAppRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`
- `AppType`: [AppTypeType](./literals.md#apptypetype)
- `AppName`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ResourceSpec`: [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)

<a id="createappresponsetypedef"></a>

## CreateAppResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAppResponseTypeDef
```

Required fields:

- `AppArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createartifactrequestrequesttypedef"></a>

## CreateArtifactRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateArtifactRequestRequestTypeDef
```

Required fields:

- `Source`: [ArtifactSourceTypeDef](./type_defs.md#artifactsourcetypedef)
- `ArtifactType`: `str`

Optional fields:

- `ArtifactName`: `str`
- `Properties`: `Mapping`\[`str`, `str`\]
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createartifactresponsetypedef"></a>

## CreateArtifactResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateArtifactResponseTypeDef
```

Required fields:

- `ArtifactArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createautomljobrequestrequesttypedef"></a>

## CreateAutoMLJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAutoMLJobRequestRequestTypeDef
```

Required fields:

- `AutoMLJobName`: `str`
- `InputDataConfig`:
  `Sequence`\[[AutoMLChannelTypeDef](./type_defs.md#automlchanneltypedef)\]
- `OutputDataConfig`:
  [AutoMLOutputDataConfigTypeDef](./type_defs.md#automloutputdataconfigtypedef)
- `RoleArn`: `str`

Optional fields:

- `ProblemType`: [ProblemTypeType](./literals.md#problemtypetype)
- `AutoMLJobObjective`:
  [AutoMLJobObjectiveTypeDef](./type_defs.md#automljobobjectivetypedef)
- `AutoMLJobConfig`:
  [AutoMLJobConfigTypeDef](./type_defs.md#automljobconfigtypedef)
- `GenerateCandidateDefinitionsOnly`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ModelDeployConfig`:
  [ModelDeployConfigTypeDef](./type_defs.md#modeldeployconfigtypedef)

<a id="createautomljobresponsetypedef"></a>

## CreateAutoMLJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateAutoMLJobResponseTypeDef
```

Required fields:

- `AutoMLJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcoderepositoryinputrequesttypedef"></a>

## CreateCodeRepositoryInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateCodeRepositoryInputRequestTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`
- `GitConfig`: [GitConfigTypeDef](./type_defs.md#gitconfigtypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createcoderepositoryoutputtypedef"></a>

## CreateCodeRepositoryOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateCodeRepositoryOutputTypeDef
```

Required fields:

- `CodeRepositoryArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcompilationjobrequestrequesttypedef"></a>

## CreateCompilationJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateCompilationJobRequestRequestTypeDef
```

Required fields:

- `CompilationJobName`: `str`
- `RoleArn`: `str`
- `OutputConfig`: [OutputConfigTypeDef](./type_defs.md#outputconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)

Optional fields:

- `ModelPackageVersionArn`: `str`
- `InputConfig`: [InputConfigTypeDef](./type_defs.md#inputconfigtypedef)
- `VpcConfig`: [NeoVpcConfigTypeDef](./type_defs.md#neovpcconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createcompilationjobresponsetypedef"></a>

## CreateCompilationJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateCompilationJobResponseTypeDef
```

Required fields:

- `CompilationJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createcontextrequestrequesttypedef"></a>

## CreateContextRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateContextRequestRequestTypeDef
```

Required fields:

- `ContextName`: `str`
- `Source`: [ContextSourceTypeDef](./type_defs.md#contextsourcetypedef)
- `ContextType`: `str`

Optional fields:

- `Description`: `str`
- `Properties`: `Mapping`\[`str`, `str`\]
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createcontextresponsetypedef"></a>

## CreateContextResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateContextResponseTypeDef
```

Required fields:

- `ContextArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdataqualityjobdefinitionrequestrequesttypedef"></a>

## CreateDataQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateDataQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`
- `DataQualityAppSpecification`:
  [DataQualityAppSpecificationTypeDef](./type_defs.md#dataqualityappspecificationtypedef)
- `DataQualityJobInput`:
  [DataQualityJobInputTypeDef](./type_defs.md#dataqualityjobinputtypedef)
- `DataQualityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `RoleArn`: `str`

Optional fields:

- `DataQualityBaselineConfig`:
  [DataQualityBaselineConfigTypeDef](./type_defs.md#dataqualitybaselineconfigtypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createdataqualityjobdefinitionresponsetypedef"></a>

## CreateDataQualityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateDataQualityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createdevicefleetrequestrequesttypedef"></a>

## CreateDeviceFleetRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateDeviceFleetRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)

Optional fields:

- `RoleArn`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `EnableIotRoleAlias`: `bool`

<a id="createdomainrequestrequesttypedef"></a>

## CreateDomainRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateDomainRequestRequestTypeDef
```

Required fields:

- `DomainName`: `str`
- `AuthMode`: [AuthModeType](./literals.md#authmodetype)
- `DefaultUserSettings`:
  [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)
- `SubnetIds`: `Sequence`\[`str`\]
- `VpcId`: `str`

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `AppNetworkAccessType`:
  [AppNetworkAccessTypeType](./literals.md#appnetworkaccesstypetype)
- `HomeEfsFileSystemKmsKeyId`: `str`
- `KmsKeyId`: `str`
- `AppSecurityGroupManagement`:
  [AppSecurityGroupManagementType](./literals.md#appsecuritygroupmanagementtype)
- `DomainSettings`:
  [DomainSettingsTypeDef](./type_defs.md#domainsettingstypedef)

<a id="createdomainresponsetypedef"></a>

## CreateDomainResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateDomainResponseTypeDef
```

Required fields:

- `DomainArn`: `str`
- `Url`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createedgepackagingjobrequestrequesttypedef"></a>

## CreateEdgePackagingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateEdgePackagingJobRequestRequestTypeDef
```

Required fields:

- `EdgePackagingJobName`: `str`
- `CompilationJobName`: `str`
- `ModelName`: `str`
- `ModelVersion`: `str`
- `RoleArn`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)

Optional fields:

- `ResourceKey`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createendpointconfiginputrequesttypedef"></a>

## CreateEndpointConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateEndpointConfigInputRequestTypeDef
```

Required fields:

- `EndpointConfigName`: `str`
- `ProductionVariants`:
  `Sequence`\[[ProductionVariantTypeDef](./type_defs.md#productionvarianttypedef)\]

Optional fields:

- `DataCaptureConfig`:
  [DataCaptureConfigTypeDef](./type_defs.md#datacaptureconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `KmsKeyId`: `str`
- `AsyncInferenceConfig`:
  [AsyncInferenceConfigTypeDef](./type_defs.md#asyncinferenceconfigtypedef)

<a id="createendpointconfigoutputtypedef"></a>

## CreateEndpointConfigOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateEndpointConfigOutputTypeDef
```

Required fields:

- `EndpointConfigArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createendpointinputrequesttypedef"></a>

## CreateEndpointInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateEndpointInputRequestTypeDef
```

Required fields:

- `EndpointName`: `str`
- `EndpointConfigName`: `str`

Optional fields:

- `DeploymentConfig`:
  [DeploymentConfigTypeDef](./type_defs.md#deploymentconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createendpointoutputtypedef"></a>

## CreateEndpointOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateEndpointOutputTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createexperimentrequestrequesttypedef"></a>

## CreateExperimentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateExperimentRequestRequestTypeDef
```

Required fields:

- `ExperimentName`: `str`

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createexperimentresponsetypedef"></a>

## CreateExperimentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateExperimentResponseTypeDef
```

Required fields:

- `ExperimentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createfeaturegrouprequestrequesttypedef"></a>

## CreateFeatureGroupRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateFeatureGroupRequestRequestTypeDef
```

Required fields:

- `FeatureGroupName`: `str`
- `RecordIdentifierFeatureName`: `str`
- `EventTimeFeatureName`: `str`
- `FeatureDefinitions`:
  `Sequence`\[[FeatureDefinitionTypeDef](./type_defs.md#featuredefinitiontypedef)\]

Optional fields:

- `OnlineStoreConfig`:
  [OnlineStoreConfigTypeDef](./type_defs.md#onlinestoreconfigtypedef)
- `OfflineStoreConfig`:
  [OfflineStoreConfigTypeDef](./type_defs.md#offlinestoreconfigtypedef)
- `RoleArn`: `str`
- `Description`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createfeaturegroupresponsetypedef"></a>

## CreateFeatureGroupResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateFeatureGroupResponseTypeDef
```

Required fields:

- `FeatureGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createflowdefinitionrequestrequesttypedef"></a>

## CreateFlowDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateFlowDefinitionRequestRequestTypeDef
```

Required fields:

- `FlowDefinitionName`: `str`
- `HumanLoopConfig`:
  [HumanLoopConfigTypeDef](./type_defs.md#humanloopconfigtypedef)
- `OutputConfig`:
  [FlowDefinitionOutputConfigTypeDef](./type_defs.md#flowdefinitionoutputconfigtypedef)
- `RoleArn`: `str`

Optional fields:

- `HumanLoopRequestSource`:
  [HumanLoopRequestSourceTypeDef](./type_defs.md#humanlooprequestsourcetypedef)
- `HumanLoopActivationConfig`:
  [HumanLoopActivationConfigTypeDef](./type_defs.md#humanloopactivationconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createflowdefinitionresponsetypedef"></a>

## CreateFlowDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateFlowDefinitionResponseTypeDef
```

Required fields:

- `FlowDefinitionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createhumantaskuirequestrequesttypedef"></a>

## CreateHumanTaskUiRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateHumanTaskUiRequestRequestTypeDef
```

Required fields:

- `HumanTaskUiName`: `str`
- `UiTemplate`: [UiTemplateTypeDef](./type_defs.md#uitemplatetypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createhumantaskuiresponsetypedef"></a>

## CreateHumanTaskUiResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateHumanTaskUiResponseTypeDef
```

Required fields:

- `HumanTaskUiArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createhyperparametertuningjobrequestrequesttypedef"></a>

## CreateHyperParameterTuningJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateHyperParameterTuningJobRequestRequestTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`
- `HyperParameterTuningJobConfig`:
  [HyperParameterTuningJobConfigTypeDef](./type_defs.md#hyperparametertuningjobconfigtypedef)

Optional fields:

- `TrainingJobDefinition`:
  [HyperParameterTrainingJobDefinitionTypeDef](./type_defs.md#hyperparametertrainingjobdefinitiontypedef)
- `TrainingJobDefinitions`:
  `Sequence`\[[HyperParameterTrainingJobDefinitionTypeDef](./type_defs.md#hyperparametertrainingjobdefinitiontypedef)\]
- `WarmStartConfig`:
  [HyperParameterTuningJobWarmStartConfigTypeDef](./type_defs.md#hyperparametertuningjobwarmstartconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createhyperparametertuningjobresponsetypedef"></a>

## CreateHyperParameterTuningJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateHyperParameterTuningJobResponseTypeDef
```

Required fields:

- `HyperParameterTuningJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createimagerequestrequesttypedef"></a>

## CreateImageRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateImageRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`
- `RoleArn`: `str`

Optional fields:

- `Description`: `str`
- `DisplayName`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createimageresponsetypedef"></a>

## CreateImageResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateImageResponseTypeDef
```

Required fields:

- `ImageArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createimageversionrequestrequesttypedef"></a>

## CreateImageVersionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateImageVersionRequestRequestTypeDef
```

Required fields:

- `BaseImage`: `str`
- `ClientToken`: `str`
- `ImageName`: `str`

<a id="createimageversionresponsetypedef"></a>

## CreateImageVersionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateImageVersionResponseTypeDef
```

Required fields:

- `ImageVersionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createinferencerecommendationsjobrequestrequesttypedef"></a>

## CreateInferenceRecommendationsJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateInferenceRecommendationsJobRequestRequestTypeDef
```

Required fields:

- `JobName`: `str`
- `JobType`:
  [RecommendationJobTypeType](./literals.md#recommendationjobtypetype)
- `RoleArn`: `str`
- `InputConfig`:
  [RecommendationJobInputConfigTypeDef](./type_defs.md#recommendationjobinputconfigtypedef)

Optional fields:

- `JobDescription`: `str`
- `StoppingConditions`:
  [RecommendationJobStoppingConditionsTypeDef](./type_defs.md#recommendationjobstoppingconditionstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createinferencerecommendationsjobresponsetypedef"></a>

## CreateInferenceRecommendationsJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateInferenceRecommendationsJobResponseTypeDef
```

Required fields:

- `JobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createlabelingjobrequestrequesttypedef"></a>

## CreateLabelingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateLabelingJobRequestRequestTypeDef
```

Required fields:

- `LabelingJobName`: `str`
- `LabelAttributeName`: `str`
- `InputConfig`:
  [LabelingJobInputConfigTypeDef](./type_defs.md#labelingjobinputconfigtypedef)
- `OutputConfig`:
  [LabelingJobOutputConfigTypeDef](./type_defs.md#labelingjoboutputconfigtypedef)
- `RoleArn`: `str`
- `HumanTaskConfig`:
  [HumanTaskConfigTypeDef](./type_defs.md#humantaskconfigtypedef)

Optional fields:

- `LabelCategoryConfigS3Uri`: `str`
- `StoppingConditions`:
  [LabelingJobStoppingConditionsTypeDef](./type_defs.md#labelingjobstoppingconditionstypedef)
- `LabelingJobAlgorithmsConfig`:
  [LabelingJobAlgorithmsConfigTypeDef](./type_defs.md#labelingjobalgorithmsconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createlabelingjobresponsetypedef"></a>

## CreateLabelingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateLabelingJobResponseTypeDef
```

Required fields:

- `LabelingJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelbiasjobdefinitionrequestrequesttypedef"></a>

## CreateModelBiasJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelBiasJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`
- `ModelBiasAppSpecification`:
  [ModelBiasAppSpecificationTypeDef](./type_defs.md#modelbiasappspecificationtypedef)
- `ModelBiasJobInput`:
  [ModelBiasJobInputTypeDef](./type_defs.md#modelbiasjobinputtypedef)
- `ModelBiasJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `RoleArn`: `str`

Optional fields:

- `ModelBiasBaselineConfig`:
  [ModelBiasBaselineConfigTypeDef](./type_defs.md#modelbiasbaselineconfigtypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createmodelbiasjobdefinitionresponsetypedef"></a>

## CreateModelBiasJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelBiasJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelexplainabilityjobdefinitionrequestrequesttypedef"></a>

## CreateModelExplainabilityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelExplainabilityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`
- `ModelExplainabilityAppSpecification`:
  [ModelExplainabilityAppSpecificationTypeDef](./type_defs.md#modelexplainabilityappspecificationtypedef)
- `ModelExplainabilityJobInput`:
  [ModelExplainabilityJobInputTypeDef](./type_defs.md#modelexplainabilityjobinputtypedef)
- `ModelExplainabilityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `RoleArn`: `str`

Optional fields:

- `ModelExplainabilityBaselineConfig`:
  [ModelExplainabilityBaselineConfigTypeDef](./type_defs.md#modelexplainabilitybaselineconfigtypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createmodelexplainabilityjobdefinitionresponsetypedef"></a>

## CreateModelExplainabilityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelExplainabilityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelinputrequesttypedef"></a>

## CreateModelInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelInputRequestTypeDef
```

Required fields:

- `ModelName`: `str`
- `ExecutionRoleArn`: `str`

Optional fields:

- `PrimaryContainer`:
  [ContainerDefinitionTypeDef](./type_defs.md#containerdefinitiontypedef)
- `Containers`:
  `Sequence`\[[ContainerDefinitionTypeDef](./type_defs.md#containerdefinitiontypedef)\]
- `InferenceExecutionConfig`:
  [InferenceExecutionConfigTypeDef](./type_defs.md#inferenceexecutionconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `EnableNetworkIsolation`: `bool`

<a id="createmodeloutputtypedef"></a>

## CreateModelOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelOutputTypeDef
```

Required fields:

- `ModelArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelpackagegroupinputrequesttypedef"></a>

## CreateModelPackageGroupInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelPackageGroupInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`

Optional fields:

- `ModelPackageGroupDescription`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createmodelpackagegroupoutputtypedef"></a>

## CreateModelPackageGroupOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelPackageGroupOutputTypeDef
```

Required fields:

- `ModelPackageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelpackageinputrequesttypedef"></a>

## CreateModelPackageInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelPackageInputRequestTypeDef
```

Optional fields:

- `ModelPackageName`: `str`
- `ModelPackageGroupName`: `str`
- `ModelPackageDescription`: `str`
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `ValidationSpecification`:
  [ModelPackageValidationSpecificationTypeDef](./type_defs.md#modelpackagevalidationspecificationtypedef)
- `SourceAlgorithmSpecification`:
  [SourceAlgorithmSpecificationTypeDef](./type_defs.md#sourcealgorithmspecificationtypedef)
- `CertifyForMarketplace`: `bool`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `ModelMetrics`: [ModelMetricsTypeDef](./type_defs.md#modelmetricstypedef)
- `ClientToken`: `str`
- `CustomerMetadataProperties`: `Mapping`\[`str`, `str`\]
- `DriftCheckBaselines`:
  [DriftCheckBaselinesTypeDef](./type_defs.md#driftcheckbaselinestypedef)
- `Domain`: `str`
- `Task`: `str`
- `SamplePayloadUrl`: `str`
- `AdditionalInferenceSpecifications`:
  `Sequence`\[[AdditionalInferenceSpecificationDefinitionTypeDef](./type_defs.md#additionalinferencespecificationdefinitiontypedef)\]

<a id="createmodelpackageoutputtypedef"></a>

## CreateModelPackageOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelPackageOutputTypeDef
```

Required fields:

- `ModelPackageArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmodelqualityjobdefinitionrequestrequesttypedef"></a>

## CreateModelQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`
- `ModelQualityAppSpecification`:
  [ModelQualityAppSpecificationTypeDef](./type_defs.md#modelqualityappspecificationtypedef)
- `ModelQualityJobInput`:
  [ModelQualityJobInputTypeDef](./type_defs.md#modelqualityjobinputtypedef)
- `ModelQualityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `RoleArn`: `str`

Optional fields:

- `ModelQualityBaselineConfig`:
  [ModelQualityBaselineConfigTypeDef](./type_defs.md#modelqualitybaselineconfigtypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createmodelqualityjobdefinitionresponsetypedef"></a>

## CreateModelQualityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateModelQualityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createmonitoringschedulerequestrequesttypedef"></a>

## CreateMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`
- `MonitoringScheduleConfig`:
  [MonitoringScheduleConfigTypeDef](./type_defs.md#monitoringscheduleconfigtypedef)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createmonitoringscheduleresponsetypedef"></a>

## CreateMonitoringScheduleResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateMonitoringScheduleResponseTypeDef
```

Required fields:

- `MonitoringScheduleArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createnotebookinstanceinputrequesttypedef"></a>

## CreateNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `RoleArn`: `str`

Optional fields:

- `SubnetId`: `str`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `KmsKeyId`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `LifecycleConfigName`: `str`
- `DirectInternetAccess`:
  [DirectInternetAccessType](./literals.md#directinternetaccesstype)
- `VolumeSizeInGB`: `int`
- `AcceleratorTypes`:
  `Sequence`\[[NotebookInstanceAcceleratorTypeType](./literals.md#notebookinstanceacceleratortypetype)\]
- `DefaultCodeRepository`: `str`
- `AdditionalCodeRepositories`: `Sequence`\[`str`\]
- `RootAccess`: [RootAccessType](./literals.md#rootaccesstype)
- `PlatformIdentifier`: `str`

<a id="createnotebookinstancelifecycleconfiginputrequesttypedef"></a>

## CreateNotebookInstanceLifecycleConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateNotebookInstanceLifecycleConfigInputRequestTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigName`: `str`

Optional fields:

- `OnCreate`:
  `Sequence`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]
- `OnStart`:
  `Sequence`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]

<a id="createnotebookinstancelifecycleconfigoutputtypedef"></a>

## CreateNotebookInstanceLifecycleConfigOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateNotebookInstanceLifecycleConfigOutputTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createnotebookinstanceoutputtypedef"></a>

## CreateNotebookInstanceOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateNotebookInstanceOutputTypeDef
```

Required fields:

- `NotebookInstanceArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpipelinerequestrequesttypedef"></a>

## CreatePipelineRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePipelineRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`
- `ClientRequestToken`: `str`
- `RoleArn`: `str`

Optional fields:

- `PipelineDisplayName`: `str`
- `PipelineDefinition`: `str`
- `PipelineDefinitionS3Location`:
  [PipelineDefinitionS3LocationTypeDef](./type_defs.md#pipelinedefinitions3locationtypedef)
- `PipelineDescription`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)

<a id="createpipelineresponsetypedef"></a>

## CreatePipelineResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePipelineResponseTypeDef
```

Required fields:

- `PipelineArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpresigneddomainurlrequestrequesttypedef"></a>

## CreatePresignedDomainUrlRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePresignedDomainUrlRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`

Optional fields:

- `SessionExpirationDurationInSeconds`: `int`
- `ExpiresInSeconds`: `int`

<a id="createpresigneddomainurlresponsetypedef"></a>

## CreatePresignedDomainUrlResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePresignedDomainUrlResponseTypeDef
```

Required fields:

- `AuthorizedUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createpresignednotebookinstanceurlinputrequesttypedef"></a>

## CreatePresignedNotebookInstanceUrlInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePresignedNotebookInstanceUrlInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

Optional fields:

- `SessionExpirationDurationInSeconds`: `int`

<a id="createpresignednotebookinstanceurloutputtypedef"></a>

## CreatePresignedNotebookInstanceUrlOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreatePresignedNotebookInstanceUrlOutputTypeDef
```

Required fields:

- `AuthorizedUrl`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createprocessingjobrequestrequesttypedef"></a>

## CreateProcessingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateProcessingJobRequestRequestTypeDef
```

Required fields:

- `ProcessingJobName`: `str`
- `ProcessingResources`:
  [ProcessingResourcesTypeDef](./type_defs.md#processingresourcestypedef)
- `AppSpecification`:
  [AppSpecificationTypeDef](./type_defs.md#appspecificationtypedef)
- `RoleArn`: `str`

Optional fields:

- `ProcessingInputs`:
  `Sequence`\[[ProcessingInputTypeDef](./type_defs.md#processinginputtypedef)\]
- `ProcessingOutputConfig`:
  [ProcessingOutputConfigTypeDef](./type_defs.md#processingoutputconfigtypedef)
- `StoppingCondition`:
  [ProcessingStoppingConditionTypeDef](./type_defs.md#processingstoppingconditiontypedef)
- `Environment`: `Mapping`\[`str`, `str`\]
- `NetworkConfig`: [NetworkConfigTypeDef](./type_defs.md#networkconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)

<a id="createprocessingjobresponsetypedef"></a>

## CreateProcessingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateProcessingJobResponseTypeDef
```

Required fields:

- `ProcessingJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createprojectinputrequesttypedef"></a>

## CreateProjectInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateProjectInputRequestTypeDef
```

Required fields:

- `ProjectName`: `str`
- `ServiceCatalogProvisioningDetails`:
  [ServiceCatalogProvisioningDetailsTypeDef](./type_defs.md#servicecatalogprovisioningdetailstypedef)

Optional fields:

- `ProjectDescription`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createprojectoutputtypedef"></a>

## CreateProjectOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateProjectOutputTypeDef
```

Required fields:

- `ProjectArn`: `str`
- `ProjectId`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createstudiolifecycleconfigrequestrequesttypedef"></a>

## CreateStudioLifecycleConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateStudioLifecycleConfigRequestRequestTypeDef
```

Required fields:

- `StudioLifecycleConfigName`: `str`
- `StudioLifecycleConfigContent`: `str`
- `StudioLifecycleConfigAppType`:
  [StudioLifecycleConfigAppTypeType](./literals.md#studiolifecycleconfigapptypetype)

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createstudiolifecycleconfigresponsetypedef"></a>

## CreateStudioLifecycleConfigResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateStudioLifecycleConfigResponseTypeDef
```

Required fields:

- `StudioLifecycleConfigArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createtrainingjobrequestrequesttypedef"></a>

## CreateTrainingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrainingJobRequestRequestTypeDef
```

Required fields:

- `TrainingJobName`: `str`
- `AlgorithmSpecification`:
  [AlgorithmSpecificationTypeDef](./type_defs.md#algorithmspecificationtypedef)
- `RoleArn`: `str`
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `ResourceConfig`:
  [ResourceConfigTypeDef](./type_defs.md#resourceconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)

Optional fields:

- `HyperParameters`: `Mapping`\[`str`, `str`\]
- `InputDataConfig`:
  `Sequence`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `EnableNetworkIsolation`: `bool`
- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableManagedSpotTraining`: `bool`
- `CheckpointConfig`:
  [CheckpointConfigTypeDef](./type_defs.md#checkpointconfigtypedef)
- `DebugHookConfig`:
  [DebugHookConfigTypeDef](./type_defs.md#debughookconfigtypedef)
- `DebugRuleConfigurations`:
  `Sequence`\[[DebugRuleConfigurationTypeDef](./type_defs.md#debugruleconfigurationtypedef)\]
- `TensorBoardOutputConfig`:
  [TensorBoardOutputConfigTypeDef](./type_defs.md#tensorboardoutputconfigtypedef)
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `ProfilerConfig`:
  [ProfilerConfigTypeDef](./type_defs.md#profilerconfigtypedef)
- `ProfilerRuleConfigurations`:
  `Sequence`\[[ProfilerRuleConfigurationTypeDef](./type_defs.md#profilerruleconfigurationtypedef)\]
- `Environment`: `Mapping`\[`str`, `str`\]
- `RetryStrategy`: [RetryStrategyTypeDef](./type_defs.md#retrystrategytypedef)

<a id="createtrainingjobresponsetypedef"></a>

## CreateTrainingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrainingJobResponseTypeDef
```

Required fields:

- `TrainingJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createtransformjobrequestrequesttypedef"></a>

## CreateTransformJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTransformJobRequestRequestTypeDef
```

Required fields:

- `TransformJobName`: `str`
- `ModelName`: `str`
- `TransformInput`:
  [TransformInputTypeDef](./type_defs.md#transforminputtypedef)
- `TransformOutput`:
  [TransformOutputTypeDef](./type_defs.md#transformoutputtypedef)
- `TransformResources`:
  [TransformResourcesTypeDef](./type_defs.md#transformresourcestypedef)

Optional fields:

- `MaxConcurrentTransforms`: `int`
- `ModelClientConfig`:
  [ModelClientConfigTypeDef](./type_defs.md#modelclientconfigtypedef)
- `MaxPayloadInMB`: `int`
- `BatchStrategy`: [BatchStrategyType](./literals.md#batchstrategytype)
- `Environment`: `Mapping`\[`str`, `str`\]
- `DataProcessing`:
  [DataProcessingTypeDef](./type_defs.md#dataprocessingtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)

<a id="createtransformjobresponsetypedef"></a>

## CreateTransformJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTransformJobResponseTypeDef
```

Required fields:

- `TransformJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createtrialcomponentrequestrequesttypedef"></a>

## CreateTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`

Optional fields:

- `DisplayName`: `str`
- `Status`:
  [TrialComponentStatusTypeDef](./type_defs.md#trialcomponentstatustypedef)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Parameters`: `Mapping`\[`str`,
  [TrialComponentParameterValueTypeDef](./type_defs.md#trialcomponentparametervaluetypedef)\]
- `InputArtifacts`: `Mapping`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `OutputArtifacts`: `Mapping`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createtrialcomponentresponsetypedef"></a>

## CreateTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createtrialrequestrequesttypedef"></a>

## CreateTrialRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrialRequestRequestTypeDef
```

Required fields:

- `TrialName`: `str`
- `ExperimentName`: `str`

Optional fields:

- `DisplayName`: `str`
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createtrialresponsetypedef"></a>

## CreateTrialResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateTrialResponseTypeDef
```

Required fields:

- `TrialArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createuserprofilerequestrequesttypedef"></a>

## CreateUserProfileRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateUserProfileRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`

Optional fields:

- `SingleSignOnUserIdentifier`: `str`
- `SingleSignOnUserValue`: `str`
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `UserSettings`: [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)

<a id="createuserprofileresponsetypedef"></a>

## CreateUserProfileResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateUserProfileResponseTypeDef
```

Required fields:

- `UserProfileArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createworkforcerequestrequesttypedef"></a>

## CreateWorkforceRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateWorkforceRequestRequestTypeDef
```

Required fields:

- `WorkforceName`: `str`

Optional fields:

- `CognitoConfig`: [CognitoConfigTypeDef](./type_defs.md#cognitoconfigtypedef)
- `OidcConfig`: [OidcConfigTypeDef](./type_defs.md#oidcconfigtypedef)
- `SourceIpConfig`:
  [SourceIpConfigTypeDef](./type_defs.md#sourceipconfigtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createworkforceresponsetypedef"></a>

## CreateWorkforceResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateWorkforceResponseTypeDef
```

Required fields:

- `WorkforceArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createworkteamrequestrequesttypedef"></a>

## CreateWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamName`: `str`
- `MemberDefinitions`:
  `Sequence`\[[MemberDefinitionTypeDef](./type_defs.md#memberdefinitiontypedef)\]
- `Description`: `str`

Optional fields:

- `WorkforceName`: `str`
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="createworkteamresponsetypedef"></a>

## CreateWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CreateWorkteamResponseTypeDef
```

Required fields:

- `WorkteamArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="customimagetypedef"></a>

## CustomImageTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import CustomImageTypeDef
```

Required fields:

- `ImageName`: `str`
- `AppImageConfigName`: `str`

Optional fields:

- `ImageVersionNumber`: `int`

<a id="datacaptureconfigsummarytypedef"></a>

## DataCaptureConfigSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataCaptureConfigSummaryTypeDef
```

Required fields:

- `EnableCapture`: `bool`
- `CaptureStatus`: [CaptureStatusType](./literals.md#capturestatustype)
- `CurrentSamplingPercentage`: `int`
- `DestinationS3Uri`: `str`
- `KmsKeyId`: `str`

<a id="datacaptureconfigtypedef"></a>

## DataCaptureConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataCaptureConfigTypeDef
```

Required fields:

- `InitialSamplingPercentage`: `int`
- `DestinationS3Uri`: `str`
- `CaptureOptions`:
  `Sequence`\[[CaptureOptionTypeDef](./type_defs.md#captureoptiontypedef)\]

Optional fields:

- `EnableCapture`: `bool`
- `KmsKeyId`: `str`
- `CaptureContentTypeHeader`:
  [CaptureContentTypeHeaderTypeDef](./type_defs.md#capturecontenttypeheadertypedef)

<a id="datacatalogconfigtypedef"></a>

## DataCatalogConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataCatalogConfigTypeDef
```

Required fields:

- `TableName`: `str`
- `Catalog`: `str`
- `Database`: `str`

<a id="dataprocessingtypedef"></a>

## DataProcessingTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataProcessingTypeDef
```

Optional fields:

- `InputFilter`: `str`
- `OutputFilter`: `str`
- `JoinSource`: [JoinSourceType](./literals.md#joinsourcetype)

<a id="dataqualityappspecificationtypedef"></a>

## DataQualityAppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataQualityAppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`

Optional fields:

- `ContainerEntrypoint`: `Sequence`\[`str`\]
- `ContainerArguments`: `Sequence`\[`str`\]
- `RecordPreprocessorSourceUri`: `str`
- `PostAnalyticsProcessorSourceUri`: `str`
- `Environment`: `Mapping`\[`str`, `str`\]

<a id="dataqualitybaselineconfigtypedef"></a>

## DataQualityBaselineConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataQualityBaselineConfigTypeDef
```

Optional fields:

- `BaseliningJobName`: `str`
- `ConstraintsResource`:
  [MonitoringConstraintsResourceTypeDef](./type_defs.md#monitoringconstraintsresourcetypedef)
- `StatisticsResource`:
  [MonitoringStatisticsResourceTypeDef](./type_defs.md#monitoringstatisticsresourcetypedef)

<a id="dataqualityjobinputtypedef"></a>

## DataQualityJobInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataQualityJobInputTypeDef
```

Required fields:

- `EndpointInput`: [EndpointInputTypeDef](./type_defs.md#endpointinputtypedef)

<a id="datasourcetypedef"></a>

## DataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DataSourceTypeDef
```

Optional fields:

- `S3DataSource`: [S3DataSourceTypeDef](./type_defs.md#s3datasourcetypedef)
- `FileSystemDataSource`:
  [FileSystemDataSourceTypeDef](./type_defs.md#filesystemdatasourcetypedef)

<a id="datasetdefinitiontypedef"></a>

## DatasetDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DatasetDefinitionTypeDef
```

Optional fields:

- `AthenaDatasetDefinition`:
  [AthenaDatasetDefinitionTypeDef](./type_defs.md#athenadatasetdefinitiontypedef)
- `RedshiftDatasetDefinition`:
  [RedshiftDatasetDefinitionTypeDef](./type_defs.md#redshiftdatasetdefinitiontypedef)
- `LocalPath`: `str`
- `DataDistributionType`:
  [DataDistributionTypeType](./literals.md#datadistributiontypetype)
- `InputMode`: [InputModeType](./literals.md#inputmodetype)

<a id="debughookconfigtypedef"></a>

## DebugHookConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DebugHookConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `LocalPath`: `str`
- `HookParameters`: `Mapping`\[`str`, `str`\]
- `CollectionConfigurations`:
  `Sequence`\[[CollectionConfigurationTypeDef](./type_defs.md#collectionconfigurationtypedef)\]

<a id="debugruleconfigurationtypedef"></a>

## DebugRuleConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DebugRuleConfigurationTypeDef
```

Required fields:

- `RuleConfigurationName`: `str`
- `RuleEvaluatorImage`: `str`

Optional fields:

- `LocalPath`: `str`
- `S3OutputPath`: `str`
- `InstanceType`:
  [ProcessingInstanceTypeType](./literals.md#processinginstancetypetype)
- `VolumeSizeInGB`: `int`
- `RuleParameters`: `Mapping`\[`str`, `str`\]

<a id="debugruleevaluationstatustypedef"></a>

## DebugRuleEvaluationStatusTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DebugRuleEvaluationStatusTypeDef
```

Optional fields:

- `RuleConfigurationName`: `str`
- `RuleEvaluationJobArn`: `str`
- `RuleEvaluationStatus`:
  [RuleEvaluationStatusType](./literals.md#ruleevaluationstatustype)
- `StatusDetails`: `str`
- `LastModifiedTime`: `datetime`

<a id="deleteactionrequestrequesttypedef"></a>

## DeleteActionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteActionRequestRequestTypeDef
```

Required fields:

- `ActionName`: `str`

<a id="deleteactionresponsetypedef"></a>

## DeleteActionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteActionResponseTypeDef
```

Required fields:

- `ActionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletealgorithminputrequesttypedef"></a>

## DeleteAlgorithmInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteAlgorithmInputRequestTypeDef
```

Required fields:

- `AlgorithmName`: `str`

<a id="deleteappimageconfigrequestrequesttypedef"></a>

## DeleteAppImageConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteAppImageConfigRequestRequestTypeDef
```

Required fields:

- `AppImageConfigName`: `str`

<a id="deleteapprequestrequesttypedef"></a>

## DeleteAppRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteAppRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`
- `AppType`: [AppTypeType](./literals.md#apptypetype)
- `AppName`: `str`

<a id="deleteartifactrequestrequesttypedef"></a>

## DeleteArtifactRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteArtifactRequestRequestTypeDef
```

Optional fields:

- `ArtifactArn`: `str`
- `Source`: [ArtifactSourceTypeDef](./type_defs.md#artifactsourcetypedef)

<a id="deleteartifactresponsetypedef"></a>

## DeleteArtifactResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteArtifactResponseTypeDef
```

Required fields:

- `ArtifactArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteassociationrequestrequesttypedef"></a>

## DeleteAssociationRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteAssociationRequestRequestTypeDef
```

Required fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`

<a id="deleteassociationresponsetypedef"></a>

## DeleteAssociationResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteAssociationResponseTypeDef
```

Required fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletecoderepositoryinputrequesttypedef"></a>

## DeleteCodeRepositoryInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteCodeRepositoryInputRequestTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`

<a id="deletecontextrequestrequesttypedef"></a>

## DeleteContextRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteContextRequestRequestTypeDef
```

Required fields:

- `ContextName`: `str`

<a id="deletecontextresponsetypedef"></a>

## DeleteContextResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteContextResponseTypeDef
```

Required fields:

- `ContextArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletedataqualityjobdefinitionrequestrequesttypedef"></a>

## DeleteDataQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteDataQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="deletedevicefleetrequestrequesttypedef"></a>

## DeleteDeviceFleetRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteDeviceFleetRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`

<a id="deletedomainrequestrequesttypedef"></a>

## DeleteDomainRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

Optional fields:

- `RetentionPolicy`:
  [RetentionPolicyTypeDef](./type_defs.md#retentionpolicytypedef)

<a id="deleteendpointconfiginputrequesttypedef"></a>

## DeleteEndpointConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteEndpointConfigInputRequestTypeDef
```

Required fields:

- `EndpointConfigName`: `str`

<a id="deleteendpointinputrequesttypedef"></a>

## DeleteEndpointInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteEndpointInputRequestTypeDef
```

Required fields:

- `EndpointName`: `str`

<a id="deleteexperimentrequestrequesttypedef"></a>

## DeleteExperimentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteExperimentRequestRequestTypeDef
```

Required fields:

- `ExperimentName`: `str`

<a id="deleteexperimentresponsetypedef"></a>

## DeleteExperimentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteExperimentResponseTypeDef
```

Required fields:

- `ExperimentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletefeaturegrouprequestrequesttypedef"></a>

## DeleteFeatureGroupRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteFeatureGroupRequestRequestTypeDef
```

Required fields:

- `FeatureGroupName`: `str`

<a id="deleteflowdefinitionrequestrequesttypedef"></a>

## DeleteFlowDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteFlowDefinitionRequestRequestTypeDef
```

Required fields:

- `FlowDefinitionName`: `str`

<a id="deletehumantaskuirequestrequesttypedef"></a>

## DeleteHumanTaskUiRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteHumanTaskUiRequestRequestTypeDef
```

Required fields:

- `HumanTaskUiName`: `str`

<a id="deleteimagerequestrequesttypedef"></a>

## DeleteImageRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteImageRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`

<a id="deleteimageversionrequestrequesttypedef"></a>

## DeleteImageVersionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteImageVersionRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`
- `Version`: `int`

<a id="deletemodelbiasjobdefinitionrequestrequesttypedef"></a>

## DeleteModelBiasJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelBiasJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="deletemodelexplainabilityjobdefinitionrequestrequesttypedef"></a>

## DeleteModelExplainabilityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelExplainabilityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="deletemodelinputrequesttypedef"></a>

## DeleteModelInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelInputRequestTypeDef
```

Required fields:

- `ModelName`: `str`

<a id="deletemodelpackagegroupinputrequesttypedef"></a>

## DeleteModelPackageGroupInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelPackageGroupInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`

<a id="deletemodelpackagegrouppolicyinputrequesttypedef"></a>

## DeleteModelPackageGroupPolicyInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelPackageGroupPolicyInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`

<a id="deletemodelpackageinputrequesttypedef"></a>

## DeleteModelPackageInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelPackageInputRequestTypeDef
```

Required fields:

- `ModelPackageName`: `str`

<a id="deletemodelqualityjobdefinitionrequestrequesttypedef"></a>

## DeleteModelQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteModelQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="deletemonitoringschedulerequestrequesttypedef"></a>

## DeleteMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`

<a id="deletenotebookinstanceinputrequesttypedef"></a>

## DeleteNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

<a id="deletenotebookinstancelifecycleconfiginputrequesttypedef"></a>

## DeleteNotebookInstanceLifecycleConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteNotebookInstanceLifecycleConfigInputRequestTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigName`: `str`

<a id="deletepipelinerequestrequesttypedef"></a>

## DeletePipelineRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeletePipelineRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`
- `ClientRequestToken`: `str`

<a id="deletepipelineresponsetypedef"></a>

## DeletePipelineResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeletePipelineResponseTypeDef
```

Required fields:

- `PipelineArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteprojectinputrequesttypedef"></a>

## DeleteProjectInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteProjectInputRequestTypeDef
```

Required fields:

- `ProjectName`: `str`

<a id="deletestudiolifecycleconfigrequestrequesttypedef"></a>

## DeleteStudioLifecycleConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteStudioLifecycleConfigRequestRequestTypeDef
```

Required fields:

- `StudioLifecycleConfigName`: `str`

<a id="deletetagsinputrequesttypedef"></a>

## DeleteTagsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteTagsInputRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`
- `TagKeys`: `Sequence`\[`str`\]

<a id="deletetrialcomponentrequestrequesttypedef"></a>

## DeleteTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`

<a id="deletetrialcomponentresponsetypedef"></a>

## DeleteTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deletetrialrequestrequesttypedef"></a>

## DeleteTrialRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteTrialRequestRequestTypeDef
```

Required fields:

- `TrialName`: `str`

<a id="deletetrialresponsetypedef"></a>

## DeleteTrialResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteTrialResponseTypeDef
```

Required fields:

- `TrialArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteuserprofilerequestrequesttypedef"></a>

## DeleteUserProfileRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteUserProfileRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`

<a id="deleteworkforcerequestrequesttypedef"></a>

## DeleteWorkforceRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteWorkforceRequestRequestTypeDef
```

Required fields:

- `WorkforceName`: `str`

<a id="deleteworkteamrequestrequesttypedef"></a>

## DeleteWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamName`: `str`

<a id="deleteworkteamresponsetypedef"></a>

## DeleteWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeleteWorkteamResponseTypeDef
```

Required fields:

- `Success`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deployedimagetypedef"></a>

## DeployedImageTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeployedImageTypeDef
```

Optional fields:

- `SpecifiedImage`: `str`
- `ResolvedImage`: `str`
- `ResolutionTime`: `datetime`

<a id="deploymentconfigtypedef"></a>

## DeploymentConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeploymentConfigTypeDef
```

Required fields:

- `BlueGreenUpdatePolicy`:
  [BlueGreenUpdatePolicyTypeDef](./type_defs.md#bluegreenupdatepolicytypedef)

Optional fields:

- `AutoRollbackConfiguration`:
  [AutoRollbackConfigTypeDef](./type_defs.md#autorollbackconfigtypedef)

<a id="deregisterdevicesrequestrequesttypedef"></a>

## DeregisterDevicesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeregisterDevicesRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `DeviceNames`: `Sequence`\[`str`\]

<a id="describeactionrequestrequesttypedef"></a>

## DescribeActionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeActionRequestRequestTypeDef
```

Required fields:

- `ActionName`: `str`

<a id="describeactionresponsetypedef"></a>

## DescribeActionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeActionResponseTypeDef
```

Required fields:

- `ActionName`: `str`
- `ActionArn`: `str`
- `Source`: [ActionSourceTypeDef](./type_defs.md#actionsourcetypedef)
- `ActionType`: `str`
- `Description`: `str`
- `Status`: [ActionStatusType](./literals.md#actionstatustype)
- `Properties`: `Dict`\[`str`, `str`\]
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `LineageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describealgorithminputrequesttypedef"></a>

## DescribeAlgorithmInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAlgorithmInputRequestTypeDef
```

Required fields:

- `AlgorithmName`: `str`

<a id="describealgorithmoutputtypedef"></a>

## DescribeAlgorithmOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAlgorithmOutputTypeDef
```

Required fields:

- `AlgorithmName`: `str`
- `AlgorithmArn`: `str`
- `AlgorithmDescription`: `str`
- `CreationTime`: `datetime`
- `TrainingSpecification`:
  [TrainingSpecificationTypeDef](./type_defs.md#trainingspecificationtypedef)
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `ValidationSpecification`:
  [AlgorithmValidationSpecificationTypeDef](./type_defs.md#algorithmvalidationspecificationtypedef)
- `AlgorithmStatus`: [AlgorithmStatusType](./literals.md#algorithmstatustype)
- `AlgorithmStatusDetails`:
  [AlgorithmStatusDetailsTypeDef](./type_defs.md#algorithmstatusdetailstypedef)
- `ProductId`: `str`
- `CertifyForMarketplace`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeappimageconfigrequestrequesttypedef"></a>

## DescribeAppImageConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAppImageConfigRequestRequestTypeDef
```

Required fields:

- `AppImageConfigName`: `str`

<a id="describeappimageconfigresponsetypedef"></a>

## DescribeAppImageConfigResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAppImageConfigResponseTypeDef
```

Required fields:

- `AppImageConfigArn`: `str`
- `AppImageConfigName`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `KernelGatewayImageConfig`:
  [KernelGatewayImageConfigTypeDef](./type_defs.md#kernelgatewayimageconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeapprequestrequesttypedef"></a>

## DescribeAppRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAppRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`
- `AppType`: [AppTypeType](./literals.md#apptypetype)
- `AppName`: `str`

<a id="describeappresponsetypedef"></a>

## DescribeAppResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAppResponseTypeDef
```

Required fields:

- `AppArn`: `str`
- `AppType`: [AppTypeType](./literals.md#apptypetype)
- `AppName`: `str`
- `DomainId`: `str`
- `UserProfileName`: `str`
- `Status`: [AppStatusType](./literals.md#appstatustype)
- `LastHealthCheckTimestamp`: `datetime`
- `LastUserActivityTimestamp`: `datetime`
- `CreationTime`: `datetime`
- `FailureReason`: `str`
- `ResourceSpec`: [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeartifactrequestrequesttypedef"></a>

## DescribeArtifactRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeArtifactRequestRequestTypeDef
```

Required fields:

- `ArtifactArn`: `str`

<a id="describeartifactresponsetypedef"></a>

## DescribeArtifactResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeArtifactResponseTypeDef
```

Required fields:

- `ArtifactName`: `str`
- `ArtifactArn`: `str`
- `Source`: [ArtifactSourceTypeDef](./type_defs.md#artifactsourcetypedef)
- `ArtifactType`: `str`
- `Properties`: `Dict`\[`str`, `str`\]
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `LineageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeautomljobrequestrequesttypedef"></a>

## DescribeAutoMLJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAutoMLJobRequestRequestTypeDef
```

Required fields:

- `AutoMLJobName`: `str`

<a id="describeautomljobresponsetypedef"></a>

## DescribeAutoMLJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeAutoMLJobResponseTypeDef
```

Required fields:

- `AutoMLJobName`: `str`
- `AutoMLJobArn`: `str`
- `InputDataConfig`:
  `List`\[[AutoMLChannelTypeDef](./type_defs.md#automlchanneltypedef)\]
- `OutputDataConfig`:
  [AutoMLOutputDataConfigTypeDef](./type_defs.md#automloutputdataconfigtypedef)
- `RoleArn`: `str`
- `AutoMLJobObjective`:
  [AutoMLJobObjectiveTypeDef](./type_defs.md#automljobobjectivetypedef)
- `ProblemType`: [ProblemTypeType](./literals.md#problemtypetype)
- `AutoMLJobConfig`:
  [AutoMLJobConfigTypeDef](./type_defs.md#automljobconfigtypedef)
- `CreationTime`: `datetime`
- `EndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`
- `PartialFailureReasons`:
  `List`\[[AutoMLPartialFailureReasonTypeDef](./type_defs.md#automlpartialfailurereasontypedef)\]
- `BestCandidate`:
  [AutoMLCandidateTypeDef](./type_defs.md#automlcandidatetypedef)
- `AutoMLJobStatus`: [AutoMLJobStatusType](./literals.md#automljobstatustype)
- `AutoMLJobSecondaryStatus`:
  [AutoMLJobSecondaryStatusType](./literals.md#automljobsecondarystatustype)
- `GenerateCandidateDefinitionsOnly`: `bool`
- `AutoMLJobArtifacts`:
  [AutoMLJobArtifactsTypeDef](./type_defs.md#automljobartifactstypedef)
- `ResolvedAttributes`:
  [ResolvedAttributesTypeDef](./type_defs.md#resolvedattributestypedef)
- `ModelDeployConfig`:
  [ModelDeployConfigTypeDef](./type_defs.md#modeldeployconfigtypedef)
- `ModelDeployResult`:
  [ModelDeployResultTypeDef](./type_defs.md#modeldeployresulttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecoderepositoryinputrequesttypedef"></a>

## DescribeCodeRepositoryInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeCodeRepositoryInputRequestTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`

<a id="describecoderepositoryoutputtypedef"></a>

## DescribeCodeRepositoryOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeCodeRepositoryOutputTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`
- `CodeRepositoryArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `GitConfig`: [GitConfigTypeDef](./type_defs.md#gitconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecompilationjobrequestrequesttypedef"></a>

## DescribeCompilationJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeCompilationJobRequestRequestTypeDef
```

Required fields:

- `CompilationJobName`: `str`

<a id="describecompilationjobresponsetypedef"></a>

## DescribeCompilationJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeCompilationJobResponseTypeDef
```

Required fields:

- `CompilationJobName`: `str`
- `CompilationJobArn`: `str`
- `CompilationJobStatus`:
  [CompilationJobStatusType](./literals.md#compilationjobstatustype)
- `CompilationStartTime`: `datetime`
- `CompilationEndTime`: `datetime`
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)
- `InferenceImage`: `str`
- `ModelPackageVersionArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`
- `ModelArtifacts`:
  [ModelArtifactsTypeDef](./type_defs.md#modelartifactstypedef)
- `ModelDigests`: [ModelDigestsTypeDef](./type_defs.md#modeldigeststypedef)
- `RoleArn`: `str`
- `InputConfig`: [InputConfigTypeDef](./type_defs.md#inputconfigtypedef)
- `OutputConfig`: [OutputConfigTypeDef](./type_defs.md#outputconfigtypedef)
- `VpcConfig`: [NeoVpcConfigTypeDef](./type_defs.md#neovpcconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describecontextrequestrequesttypedef"></a>

## DescribeContextRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeContextRequestRequestTypeDef
```

Required fields:

- `ContextName`: `str`

<a id="describecontextresponsetypedef"></a>

## DescribeContextResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeContextResponseTypeDef
```

Required fields:

- `ContextName`: `str`
- `ContextArn`: `str`
- `Source`: [ContextSourceTypeDef](./type_defs.md#contextsourcetypedef)
- `ContextType`: `str`
- `Description`: `str`
- `Properties`: `Dict`\[`str`, `str`\]
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LineageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedataqualityjobdefinitionrequestrequesttypedef"></a>

## DescribeDataQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDataQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="describedataqualityjobdefinitionresponsetypedef"></a>

## DescribeDataQualityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDataQualityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `JobDefinitionName`: `str`
- `CreationTime`: `datetime`
- `DataQualityBaselineConfig`:
  [DataQualityBaselineConfigTypeDef](./type_defs.md#dataqualitybaselineconfigtypedef)
- `DataQualityAppSpecification`:
  [DataQualityAppSpecificationTypeDef](./type_defs.md#dataqualityappspecificationtypedef)
- `DataQualityJobInput`:
  [DataQualityJobInputTypeDef](./type_defs.md#dataqualityjobinputtypedef)
- `DataQualityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `RoleArn`: `str`
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedevicefleetrequestrequesttypedef"></a>

## DescribeDeviceFleetRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDeviceFleetRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`

<a id="describedevicefleetresponsetypedef"></a>

## DescribeDeviceFleetResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDeviceFleetResponseTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `DeviceFleetArn`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)
- `Description`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `RoleArn`: `str`
- `IotRoleAlias`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedevicerequestrequesttypedef"></a>

## DescribeDeviceRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDeviceRequestRequestTypeDef
```

Required fields:

- `DeviceName`: `str`
- `DeviceFleetName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="describedeviceresponsetypedef"></a>

## DescribeDeviceResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDeviceResponseTypeDef
```

Required fields:

- `DeviceArn`: `str`
- `DeviceName`: `str`
- `Description`: `str`
- `DeviceFleetName`: `str`
- `IotThingName`: `str`
- `RegistrationTime`: `datetime`
- `LatestHeartbeat`: `datetime`
- `Models`: `List`\[[EdgeModelTypeDef](./type_defs.md#edgemodeltypedef)\]
- `MaxModels`: `int`
- `NextToken`: `str`
- `AgentVersion`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describedomainrequestrequesttypedef"></a>

## DescribeDomainRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

<a id="describedomainresponsetypedef"></a>

## DescribeDomainResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeDomainResponseTypeDef
```

Required fields:

- `DomainArn`: `str`
- `DomainId`: `str`
- `DomainName`: `str`
- `HomeEfsFileSystemId`: `str`
- `SingleSignOnManagedApplicationInstanceId`: `str`
- `Status`: [DomainStatusType](./literals.md#domainstatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`
- `AuthMode`: [AuthModeType](./literals.md#authmodetype)
- `DefaultUserSettings`:
  [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)
- `AppNetworkAccessType`:
  [AppNetworkAccessTypeType](./literals.md#appnetworkaccesstypetype)
- `HomeEfsFileSystemKmsKeyId`: `str`
- `SubnetIds`: `List`\[`str`\]
- `Url`: `str`
- `VpcId`: `str`
- `KmsKeyId`: `str`
- `DomainSettings`:
  [DomainSettingsTypeDef](./type_defs.md#domainsettingstypedef)
- `AppSecurityGroupManagement`:
  [AppSecurityGroupManagementType](./literals.md#appsecuritygroupmanagementtype)
- `SecurityGroupIdForDomainBoundary`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeedgepackagingjobrequestrequesttypedef"></a>

## DescribeEdgePackagingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEdgePackagingJobRequestRequestTypeDef
```

Required fields:

- `EdgePackagingJobName`: `str`

<a id="describeedgepackagingjobresponsetypedef"></a>

## DescribeEdgePackagingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEdgePackagingJobResponseTypeDef
```

Required fields:

- `EdgePackagingJobArn`: `str`
- `EdgePackagingJobName`: `str`
- `CompilationJobName`: `str`
- `ModelName`: `str`
- `ModelVersion`: `str`
- `RoleArn`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)
- `ResourceKey`: `str`
- `EdgePackagingJobStatus`:
  [EdgePackagingJobStatusType](./literals.md#edgepackagingjobstatustype)
- `EdgePackagingJobStatusMessage`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `ModelArtifact`: `str`
- `ModelSignature`: `str`
- `PresetDeploymentOutput`:
  [EdgePresetDeploymentOutputTypeDef](./type_defs.md#edgepresetdeploymentoutputtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeendpointconfiginputrequesttypedef"></a>

## DescribeEndpointConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEndpointConfigInputRequestTypeDef
```

Required fields:

- `EndpointConfigName`: `str`

<a id="describeendpointconfigoutputtypedef"></a>

## DescribeEndpointConfigOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEndpointConfigOutputTypeDef
```

Required fields:

- `EndpointConfigName`: `str`
- `EndpointConfigArn`: `str`
- `ProductionVariants`:
  `List`\[[ProductionVariantTypeDef](./type_defs.md#productionvarianttypedef)\]
- `DataCaptureConfig`:
  [DataCaptureConfigTypeDef](./type_defs.md#datacaptureconfigtypedef)
- `KmsKeyId`: `str`
- `CreationTime`: `datetime`
- `AsyncInferenceConfig`:
  [AsyncInferenceConfigTypeDef](./type_defs.md#asyncinferenceconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeendpointinputrequesttypedef"></a>

## DescribeEndpointInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEndpointInputRequestTypeDef
```

Required fields:

- `EndpointName`: `str`

<a id="describeendpointoutputtypedef"></a>

## DescribeEndpointOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeEndpointOutputTypeDef
```

Required fields:

- `EndpointName`: `str`
- `EndpointArn`: `str`
- `EndpointConfigName`: `str`
- `ProductionVariants`:
  `List`\[[ProductionVariantSummaryTypeDef](./type_defs.md#productionvariantsummarytypedef)\]
- `DataCaptureConfig`:
  [DataCaptureConfigSummaryTypeDef](./type_defs.md#datacaptureconfigsummarytypedef)
- `EndpointStatus`: [EndpointStatusType](./literals.md#endpointstatustype)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LastDeploymentConfig`:
  [DeploymentConfigTypeDef](./type_defs.md#deploymentconfigtypedef)
- `AsyncInferenceConfig`:
  [AsyncInferenceConfigTypeDef](./type_defs.md#asyncinferenceconfigtypedef)
- `PendingDeploymentSummary`:
  [PendingDeploymentSummaryTypeDef](./type_defs.md#pendingdeploymentsummarytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeexperimentrequestrequesttypedef"></a>

## DescribeExperimentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeExperimentRequestRequestTypeDef
```

Required fields:

- `ExperimentName`: `str`

<a id="describeexperimentresponsetypedef"></a>

## DescribeExperimentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeExperimentResponseTypeDef
```

Required fields:

- `ExperimentName`: `str`
- `ExperimentArn`: `str`
- `DisplayName`: `str`
- `Source`: [ExperimentSourceTypeDef](./type_defs.md#experimentsourcetypedef)
- `Description`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describefeaturegrouprequestrequesttypedef"></a>

## DescribeFeatureGroupRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeFeatureGroupRequestRequestTypeDef
```

Required fields:

- `FeatureGroupName`: `str`

Optional fields:

- `NextToken`: `str`

<a id="describefeaturegroupresponsetypedef"></a>

## DescribeFeatureGroupResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeFeatureGroupResponseTypeDef
```

Required fields:

- `FeatureGroupArn`: `str`
- `FeatureGroupName`: `str`
- `RecordIdentifierFeatureName`: `str`
- `EventTimeFeatureName`: `str`
- `FeatureDefinitions`:
  `List`\[[FeatureDefinitionTypeDef](./type_defs.md#featuredefinitiontypedef)\]
- `CreationTime`: `datetime`
- `OnlineStoreConfig`:
  [OnlineStoreConfigTypeDef](./type_defs.md#onlinestoreconfigtypedef)
- `OfflineStoreConfig`:
  [OfflineStoreConfigTypeDef](./type_defs.md#offlinestoreconfigtypedef)
- `RoleArn`: `str`
- `FeatureGroupStatus`:
  [FeatureGroupStatusType](./literals.md#featuregroupstatustype)
- `OfflineStoreStatus`:
  [OfflineStoreStatusTypeDef](./type_defs.md#offlinestorestatustypedef)
- `FailureReason`: `str`
- `Description`: `str`
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeflowdefinitionrequestrequesttypedef"></a>

## DescribeFlowDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeFlowDefinitionRequestRequestTypeDef
```

Required fields:

- `FlowDefinitionName`: `str`

<a id="describeflowdefinitionresponsetypedef"></a>

## DescribeFlowDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeFlowDefinitionResponseTypeDef
```

Required fields:

- `FlowDefinitionArn`: `str`
- `FlowDefinitionName`: `str`
- `FlowDefinitionStatus`:
  [FlowDefinitionStatusType](./literals.md#flowdefinitionstatustype)
- `CreationTime`: `datetime`
- `HumanLoopRequestSource`:
  [HumanLoopRequestSourceTypeDef](./type_defs.md#humanlooprequestsourcetypedef)
- `HumanLoopActivationConfig`:
  [HumanLoopActivationConfigTypeDef](./type_defs.md#humanloopactivationconfigtypedef)
- `HumanLoopConfig`:
  [HumanLoopConfigTypeDef](./type_defs.md#humanloopconfigtypedef)
- `OutputConfig`:
  [FlowDefinitionOutputConfigTypeDef](./type_defs.md#flowdefinitionoutputconfigtypedef)
- `RoleArn`: `str`
- `FailureReason`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describehumantaskuirequestrequesttypedef"></a>

## DescribeHumanTaskUiRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeHumanTaskUiRequestRequestTypeDef
```

Required fields:

- `HumanTaskUiName`: `str`

<a id="describehumantaskuiresponsetypedef"></a>

## DescribeHumanTaskUiResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeHumanTaskUiResponseTypeDef
```

Required fields:

- `HumanTaskUiArn`: `str`
- `HumanTaskUiName`: `str`
- `HumanTaskUiStatus`:
  [HumanTaskUiStatusType](./literals.md#humantaskuistatustype)
- `CreationTime`: `datetime`
- `UiTemplate`: [UiTemplateInfoTypeDef](./type_defs.md#uitemplateinfotypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describehyperparametertuningjobrequestrequesttypedef"></a>

## DescribeHyperParameterTuningJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeHyperParameterTuningJobRequestRequestTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`

<a id="describehyperparametertuningjobresponsetypedef"></a>

## DescribeHyperParameterTuningJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeHyperParameterTuningJobResponseTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`
- `HyperParameterTuningJobArn`: `str`
- `HyperParameterTuningJobConfig`:
  [HyperParameterTuningJobConfigTypeDef](./type_defs.md#hyperparametertuningjobconfigtypedef)
- `TrainingJobDefinition`:
  [HyperParameterTrainingJobDefinitionTypeDef](./type_defs.md#hyperparametertrainingjobdefinitiontypedef)
- `TrainingJobDefinitions`:
  `List`\[[HyperParameterTrainingJobDefinitionTypeDef](./type_defs.md#hyperparametertrainingjobdefinitiontypedef)\]
- `HyperParameterTuningJobStatus`:
  [HyperParameterTuningJobStatusType](./literals.md#hyperparametertuningjobstatustype)
- `CreationTime`: `datetime`
- `HyperParameterTuningEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `TrainingJobStatusCounters`:
  [TrainingJobStatusCountersTypeDef](./type_defs.md#trainingjobstatuscounterstypedef)
- `ObjectiveStatusCounters`:
  [ObjectiveStatusCountersTypeDef](./type_defs.md#objectivestatuscounterstypedef)
- `BestTrainingJob`:
  [HyperParameterTrainingJobSummaryTypeDef](./type_defs.md#hyperparametertrainingjobsummarytypedef)
- `OverallBestTrainingJob`:
  [HyperParameterTrainingJobSummaryTypeDef](./type_defs.md#hyperparametertrainingjobsummarytypedef)
- `WarmStartConfig`:
  [HyperParameterTuningJobWarmStartConfigTypeDef](./type_defs.md#hyperparametertuningjobwarmstartconfigtypedef)
- `FailureReason`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimagerequestrequesttypedef"></a>

## DescribeImageRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeImageRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`

<a id="describeimageresponsetypedef"></a>

## DescribeImageResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeImageResponseTypeDef
```

Required fields:

- `CreationTime`: `datetime`
- `Description`: `str`
- `DisplayName`: `str`
- `FailureReason`: `str`
- `ImageArn`: `str`
- `ImageName`: `str`
- `ImageStatus`: [ImageStatusType](./literals.md#imagestatustype)
- `LastModifiedTime`: `datetime`
- `RoleArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeimageversionrequestrequesttypedef"></a>

## DescribeImageVersionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeImageVersionRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`

Optional fields:

- `Version`: `int`

<a id="describeimageversionresponsetypedef"></a>

## DescribeImageVersionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeImageVersionResponseTypeDef
```

Required fields:

- `BaseImage`: `str`
- `ContainerImage`: `str`
- `CreationTime`: `datetime`
- `FailureReason`: `str`
- `ImageArn`: `str`
- `ImageVersionArn`: `str`
- `ImageVersionStatus`:
  [ImageVersionStatusType](./literals.md#imageversionstatustype)
- `LastModifiedTime`: `datetime`
- `Version`: `int`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeinferencerecommendationsjobrequestrequesttypedef"></a>

## DescribeInferenceRecommendationsJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeInferenceRecommendationsJobRequestRequestTypeDef
```

Required fields:

- `JobName`: `str`

<a id="describeinferencerecommendationsjobresponsetypedef"></a>

## DescribeInferenceRecommendationsJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeInferenceRecommendationsJobResponseTypeDef
```

Required fields:

- `JobName`: `str`
- `JobDescription`: `str`
- `JobType`:
  [RecommendationJobTypeType](./literals.md#recommendationjobtypetype)
- `JobArn`: `str`
- `RoleArn`: `str`
- `Status`:
  [RecommendationJobStatusType](./literals.md#recommendationjobstatustype)
- `CreationTime`: `datetime`
- `CompletionTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`
- `InputConfig`:
  [RecommendationJobInputConfigTypeDef](./type_defs.md#recommendationjobinputconfigtypedef)
- `StoppingConditions`:
  [RecommendationJobStoppingConditionsTypeDef](./type_defs.md#recommendationjobstoppingconditionstypedef)
- `InferenceRecommendations`:
  `List`\[[InferenceRecommendationTypeDef](./type_defs.md#inferencerecommendationtypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describelabelingjobrequestrequesttypedef"></a>

## DescribeLabelingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeLabelingJobRequestRequestTypeDef
```

Required fields:

- `LabelingJobName`: `str`

<a id="describelabelingjobresponsetypedef"></a>

## DescribeLabelingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeLabelingJobResponseTypeDef
```

Required fields:

- `LabelingJobStatus`:
  [LabelingJobStatusType](./literals.md#labelingjobstatustype)
- `LabelCounters`: [LabelCountersTypeDef](./type_defs.md#labelcounterstypedef)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `JobReferenceCode`: `str`
- `LabelingJobName`: `str`
- `LabelingJobArn`: `str`
- `LabelAttributeName`: `str`
- `InputConfig`:
  [LabelingJobInputConfigTypeDef](./type_defs.md#labelingjobinputconfigtypedef)
- `OutputConfig`:
  [LabelingJobOutputConfigTypeDef](./type_defs.md#labelingjoboutputconfigtypedef)
- `RoleArn`: `str`
- `LabelCategoryConfigS3Uri`: `str`
- `StoppingConditions`:
  [LabelingJobStoppingConditionsTypeDef](./type_defs.md#labelingjobstoppingconditionstypedef)
- `LabelingJobAlgorithmsConfig`:
  [LabelingJobAlgorithmsConfigTypeDef](./type_defs.md#labelingjobalgorithmsconfigtypedef)
- `HumanTaskConfig`:
  [HumanTaskConfigTypeDef](./type_defs.md#humantaskconfigtypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `LabelingJobOutput`:
  [LabelingJobOutputTypeDef](./type_defs.md#labelingjoboutputtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describelineagegrouprequestrequesttypedef"></a>

## DescribeLineageGroupRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeLineageGroupRequestRequestTypeDef
```

Required fields:

- `LineageGroupName`: `str`

<a id="describelineagegroupresponsetypedef"></a>

## DescribeLineageGroupResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeLineageGroupResponseTypeDef
```

Required fields:

- `LineageGroupName`: `str`
- `LineageGroupArn`: `str`
- `DisplayName`: `str`
- `Description`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelbiasjobdefinitionrequestrequesttypedef"></a>

## DescribeModelBiasJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelBiasJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="describemodelbiasjobdefinitionresponsetypedef"></a>

## DescribeModelBiasJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelBiasJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `JobDefinitionName`: `str`
- `CreationTime`: `datetime`
- `ModelBiasBaselineConfig`:
  [ModelBiasBaselineConfigTypeDef](./type_defs.md#modelbiasbaselineconfigtypedef)
- `ModelBiasAppSpecification`:
  [ModelBiasAppSpecificationTypeDef](./type_defs.md#modelbiasappspecificationtypedef)
- `ModelBiasJobInput`:
  [ModelBiasJobInputTypeDef](./type_defs.md#modelbiasjobinputtypedef)
- `ModelBiasJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `RoleArn`: `str`
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelexplainabilityjobdefinitionrequestrequesttypedef"></a>

## DescribeModelExplainabilityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelExplainabilityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="describemodelexplainabilityjobdefinitionresponsetypedef"></a>

## DescribeModelExplainabilityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelExplainabilityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `JobDefinitionName`: `str`
- `CreationTime`: `datetime`
- `ModelExplainabilityBaselineConfig`:
  [ModelExplainabilityBaselineConfigTypeDef](./type_defs.md#modelexplainabilitybaselineconfigtypedef)
- `ModelExplainabilityAppSpecification`:
  [ModelExplainabilityAppSpecificationTypeDef](./type_defs.md#modelexplainabilityappspecificationtypedef)
- `ModelExplainabilityJobInput`:
  [ModelExplainabilityJobInputTypeDef](./type_defs.md#modelexplainabilityjobinputtypedef)
- `ModelExplainabilityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `RoleArn`: `str`
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelinputrequesttypedef"></a>

## DescribeModelInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelInputRequestTypeDef
```

Required fields:

- `ModelName`: `str`

<a id="describemodeloutputtypedef"></a>

## DescribeModelOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelOutputTypeDef
```

Required fields:

- `ModelName`: `str`
- `PrimaryContainer`:
  [ContainerDefinitionTypeDef](./type_defs.md#containerdefinitiontypedef)
- `Containers`:
  `List`\[[ContainerDefinitionTypeDef](./type_defs.md#containerdefinitiontypedef)\]
- `InferenceExecutionConfig`:
  [InferenceExecutionConfigTypeDef](./type_defs.md#inferenceexecutionconfigtypedef)
- `ExecutionRoleArn`: `str`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `CreationTime`: `datetime`
- `ModelArn`: `str`
- `EnableNetworkIsolation`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelpackagegroupinputrequesttypedef"></a>

## DescribeModelPackageGroupInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelPackageGroupInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`

<a id="describemodelpackagegroupoutputtypedef"></a>

## DescribeModelPackageGroupOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelPackageGroupOutputTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`
- `ModelPackageGroupArn`: `str`
- `ModelPackageGroupDescription`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ModelPackageGroupStatus`:
  [ModelPackageGroupStatusType](./literals.md#modelpackagegroupstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelpackageinputrequesttypedef"></a>

## DescribeModelPackageInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelPackageInputRequestTypeDef
```

Required fields:

- `ModelPackageName`: `str`

<a id="describemodelpackageoutputtypedef"></a>

## DescribeModelPackageOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelPackageOutputTypeDef
```

Required fields:

- `ModelPackageName`: `str`
- `ModelPackageGroupName`: `str`
- `ModelPackageVersion`: `int`
- `ModelPackageArn`: `str`
- `ModelPackageDescription`: `str`
- `CreationTime`: `datetime`
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `SourceAlgorithmSpecification`:
  [SourceAlgorithmSpecificationTypeDef](./type_defs.md#sourcealgorithmspecificationtypedef)
- `ValidationSpecification`:
  [ModelPackageValidationSpecificationTypeDef](./type_defs.md#modelpackagevalidationspecificationtypedef)
- `ModelPackageStatus`:
  [ModelPackageStatusType](./literals.md#modelpackagestatustype)
- `ModelPackageStatusDetails`:
  [ModelPackageStatusDetailsTypeDef](./type_defs.md#modelpackagestatusdetailstypedef)
- `CertifyForMarketplace`: `bool`
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `ModelMetrics`: [ModelMetricsTypeDef](./type_defs.md#modelmetricstypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ApprovalDescription`: `str`
- `CustomerMetadataProperties`: `Dict`\[`str`, `str`\]
- `DriftCheckBaselines`:
  [DriftCheckBaselinesTypeDef](./type_defs.md#driftcheckbaselinestypedef)
- `Domain`: `str`
- `Task`: `str`
- `SamplePayloadUrl`: `str`
- `AdditionalInferenceSpecifications`:
  `List`\[[AdditionalInferenceSpecificationDefinitionTypeDef](./type_defs.md#additionalinferencespecificationdefinitiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemodelqualityjobdefinitionrequestrequesttypedef"></a>

## DescribeModelQualityJobDefinitionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelQualityJobDefinitionRequestRequestTypeDef
```

Required fields:

- `JobDefinitionName`: `str`

<a id="describemodelqualityjobdefinitionresponsetypedef"></a>

## DescribeModelQualityJobDefinitionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeModelQualityJobDefinitionResponseTypeDef
```

Required fields:

- `JobDefinitionArn`: `str`
- `JobDefinitionName`: `str`
- `CreationTime`: `datetime`
- `ModelQualityBaselineConfig`:
  [ModelQualityBaselineConfigTypeDef](./type_defs.md#modelqualitybaselineconfigtypedef)
- `ModelQualityAppSpecification`:
  [ModelQualityAppSpecificationTypeDef](./type_defs.md#modelqualityappspecificationtypedef)
- `ModelQualityJobInput`:
  [ModelQualityJobInputTypeDef](./type_defs.md#modelqualityjobinputtypedef)
- `ModelQualityJobOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `JobResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `NetworkConfig`:
  [MonitoringNetworkConfigTypeDef](./type_defs.md#monitoringnetworkconfigtypedef)
- `RoleArn`: `str`
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describemonitoringschedulerequestrequesttypedef"></a>

## DescribeMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`

<a id="describemonitoringscheduleresponsetypedef"></a>

## DescribeMonitoringScheduleResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeMonitoringScheduleResponseTypeDef
```

Required fields:

- `MonitoringScheduleArn`: `str`
- `MonitoringScheduleName`: `str`
- `MonitoringScheduleStatus`:
  [ScheduleStatusType](./literals.md#schedulestatustype)
- `MonitoringType`: [MonitoringTypeType](./literals.md#monitoringtypetype)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `MonitoringScheduleConfig`:
  [MonitoringScheduleConfigTypeDef](./type_defs.md#monitoringscheduleconfigtypedef)
- `EndpointName`: `str`
- `LastMonitoringExecutionSummary`:
  [MonitoringExecutionSummaryTypeDef](./type_defs.md#monitoringexecutionsummarytypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describenotebookinstanceinputrequesttypedef"></a>

## DescribeNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

<a id="describenotebookinstancelifecycleconfiginputrequesttypedef"></a>

## DescribeNotebookInstanceLifecycleConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeNotebookInstanceLifecycleConfigInputRequestTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigName`: `str`

<a id="describenotebookinstancelifecycleconfigoutputtypedef"></a>

## DescribeNotebookInstanceLifecycleConfigOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeNotebookInstanceLifecycleConfigOutputTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigArn`: `str`
- `NotebookInstanceLifecycleConfigName`: `str`
- `OnCreate`:
  `List`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]
- `OnStart`:
  `List`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]
- `LastModifiedTime`: `datetime`
- `CreationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describenotebookinstanceoutputtypedef"></a>

## DescribeNotebookInstanceOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeNotebookInstanceOutputTypeDef
```

Required fields:

- `NotebookInstanceArn`: `str`
- `NotebookInstanceName`: `str`
- `NotebookInstanceStatus`:
  [NotebookInstanceStatusType](./literals.md#notebookinstancestatustype)
- `FailureReason`: `str`
- `Url`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `SubnetId`: `str`
- `SecurityGroups`: `List`\[`str`\]
- `RoleArn`: `str`
- `KmsKeyId`: `str`
- `NetworkInterfaceId`: `str`
- `LastModifiedTime`: `datetime`
- `CreationTime`: `datetime`
- `NotebookInstanceLifecycleConfigName`: `str`
- `DirectInternetAccess`:
  [DirectInternetAccessType](./literals.md#directinternetaccesstype)
- `VolumeSizeInGB`: `int`
- `AcceleratorTypes`:
  `List`\[[NotebookInstanceAcceleratorTypeType](./literals.md#notebookinstanceacceleratortypetype)\]
- `DefaultCodeRepository`: `str`
- `AdditionalCodeRepositories`: `List`\[`str`\]
- `RootAccess`: [RootAccessType](./literals.md#rootaccesstype)
- `PlatformIdentifier`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepipelinedefinitionforexecutionrequestrequesttypedef"></a>

## DescribePipelineDefinitionForExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineDefinitionForExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`

<a id="describepipelinedefinitionforexecutionresponsetypedef"></a>

## DescribePipelineDefinitionForExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineDefinitionForExecutionResponseTypeDef
```

Required fields:

- `PipelineDefinition`: `str`
- `CreationTime`: `datetime`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepipelineexecutionrequestrequesttypedef"></a>

## DescribePipelineExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`

<a id="describepipelineexecutionresponsetypedef"></a>

## DescribePipelineExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineExecutionResponseTypeDef
```

Required fields:

- `PipelineArn`: `str`
- `PipelineExecutionArn`: `str`
- `PipelineExecutionDisplayName`: `str`
- `PipelineExecutionStatus`:
  [PipelineExecutionStatusType](./literals.md#pipelineexecutionstatustype)
- `PipelineExecutionDescription`: `str`
- `PipelineExperimentConfig`:
  [PipelineExperimentConfigTypeDef](./type_defs.md#pipelineexperimentconfigtypedef)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describepipelinerequestrequesttypedef"></a>

## DescribePipelineRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`

<a id="describepipelineresponsetypedef"></a>

## DescribePipelineResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribePipelineResponseTypeDef
```

Required fields:

- `PipelineArn`: `str`
- `PipelineName`: `str`
- `PipelineDisplayName`: `str`
- `PipelineDefinition`: `str`
- `PipelineDescription`: `str`
- `RoleArn`: `str`
- `PipelineStatus`: `Literal['Active']` (see
  [PipelineStatusType](./literals.md#pipelinestatustype))
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LastRunTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeprocessingjobrequestrequesttypedef"></a>

## DescribeProcessingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeProcessingJobRequestRequestTypeDef
```

Required fields:

- `ProcessingJobName`: `str`

<a id="describeprocessingjobresponsetypedef"></a>

## DescribeProcessingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeProcessingJobResponseTypeDef
```

Required fields:

- `ProcessingInputs`:
  `List`\[[ProcessingInputTypeDef](./type_defs.md#processinginputtypedef)\]
- `ProcessingOutputConfig`:
  [ProcessingOutputConfigTypeDef](./type_defs.md#processingoutputconfigtypedef)
- `ProcessingJobName`: `str`
- `ProcessingResources`:
  [ProcessingResourcesTypeDef](./type_defs.md#processingresourcestypedef)
- `StoppingCondition`:
  [ProcessingStoppingConditionTypeDef](./type_defs.md#processingstoppingconditiontypedef)
- `AppSpecification`:
  [AppSpecificationTypeDef](./type_defs.md#appspecificationtypedef)
- `Environment`: `Dict`\[`str`, `str`\]
- `NetworkConfig`: [NetworkConfigTypeDef](./type_defs.md#networkconfigtypedef)
- `RoleArn`: `str`
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `ProcessingJobArn`: `str`
- `ProcessingJobStatus`:
  [ProcessingJobStatusType](./literals.md#processingjobstatustype)
- `ExitMessage`: `str`
- `FailureReason`: `str`
- `ProcessingEndTime`: `datetime`
- `ProcessingStartTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `CreationTime`: `datetime`
- `MonitoringScheduleArn`: `str`
- `AutoMLJobArn`: `str`
- `TrainingJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeprojectinputrequesttypedef"></a>

## DescribeProjectInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeProjectInputRequestTypeDef
```

Required fields:

- `ProjectName`: `str`

<a id="describeprojectoutputtypedef"></a>

## DescribeProjectOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeProjectOutputTypeDef
```

Required fields:

- `ProjectArn`: `str`
- `ProjectName`: `str`
- `ProjectId`: `str`
- `ProjectDescription`: `str`
- `ServiceCatalogProvisioningDetails`:
  [ServiceCatalogProvisioningDetailsTypeDef](./type_defs.md#servicecatalogprovisioningdetailstypedef)
- `ServiceCatalogProvisionedProductDetails`:
  [ServiceCatalogProvisionedProductDetailsTypeDef](./type_defs.md#servicecatalogprovisionedproductdetailstypedef)
- `ProjectStatus`: [ProjectStatusType](./literals.md#projectstatustype)
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describestudiolifecycleconfigrequestrequesttypedef"></a>

## DescribeStudioLifecycleConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeStudioLifecycleConfigRequestRequestTypeDef
```

Required fields:

- `StudioLifecycleConfigName`: `str`

<a id="describestudiolifecycleconfigresponsetypedef"></a>

## DescribeStudioLifecycleConfigResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeStudioLifecycleConfigResponseTypeDef
```

Required fields:

- `StudioLifecycleConfigArn`: `str`
- `StudioLifecycleConfigName`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `StudioLifecycleConfigContent`: `str`
- `StudioLifecycleConfigAppType`:
  [StudioLifecycleConfigAppTypeType](./literals.md#studiolifecycleconfigapptypetype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describesubscribedworkteamrequestrequesttypedef"></a>

## DescribeSubscribedWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeSubscribedWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamArn`: `str`

<a id="describesubscribedworkteamresponsetypedef"></a>

## DescribeSubscribedWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeSubscribedWorkteamResponseTypeDef
```

Required fields:

- `SubscribedWorkteam`:
  [SubscribedWorkteamTypeDef](./type_defs.md#subscribedworkteamtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetrainingjobrequestrequesttypedef"></a>

## DescribeTrainingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrainingJobRequestRequestTypeDef
```

Required fields:

- `TrainingJobName`: `str`

<a id="describetrainingjobresponsetypedef"></a>

## DescribeTrainingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrainingJobResponseTypeDef
```

Required fields:

- `TrainingJobName`: `str`
- `TrainingJobArn`: `str`
- `TuningJobArn`: `str`
- `LabelingJobArn`: `str`
- `AutoMLJobArn`: `str`
- `ModelArtifacts`:
  [ModelArtifactsTypeDef](./type_defs.md#modelartifactstypedef)
- `TrainingJobStatus`:
  [TrainingJobStatusType](./literals.md#trainingjobstatustype)
- `SecondaryStatus`: [SecondaryStatusType](./literals.md#secondarystatustype)
- `FailureReason`: `str`
- `HyperParameters`: `Dict`\[`str`, `str`\]
- `AlgorithmSpecification`:
  [AlgorithmSpecificationTypeDef](./type_defs.md#algorithmspecificationtypedef)
- `RoleArn`: `str`
- `InputDataConfig`: `List`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `ResourceConfig`:
  [ResourceConfigTypeDef](./type_defs.md#resourceconfigtypedef)
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)
- `CreationTime`: `datetime`
- `TrainingStartTime`: `datetime`
- `TrainingEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `SecondaryStatusTransitions`:
  `List`\[[SecondaryStatusTransitionTypeDef](./type_defs.md#secondarystatustransitiontypedef)\]
- `FinalMetricDataList`:
  `List`\[[MetricDataTypeDef](./type_defs.md#metricdatatypedef)\]
- `EnableNetworkIsolation`: `bool`
- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableManagedSpotTraining`: `bool`
- `CheckpointConfig`:
  [CheckpointConfigTypeDef](./type_defs.md#checkpointconfigtypedef)
- `TrainingTimeInSeconds`: `int`
- `BillableTimeInSeconds`: `int`
- `DebugHookConfig`:
  [DebugHookConfigTypeDef](./type_defs.md#debughookconfigtypedef)
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `DebugRuleConfigurations`:
  `List`\[[DebugRuleConfigurationTypeDef](./type_defs.md#debugruleconfigurationtypedef)\]
- `TensorBoardOutputConfig`:
  [TensorBoardOutputConfigTypeDef](./type_defs.md#tensorboardoutputconfigtypedef)
- `DebugRuleEvaluationStatuses`:
  `List`\[[DebugRuleEvaluationStatusTypeDef](./type_defs.md#debugruleevaluationstatustypedef)\]
- `ProfilerConfig`:
  [ProfilerConfigTypeDef](./type_defs.md#profilerconfigtypedef)
- `ProfilerRuleConfigurations`:
  `List`\[[ProfilerRuleConfigurationTypeDef](./type_defs.md#profilerruleconfigurationtypedef)\]
- `ProfilerRuleEvaluationStatuses`:
  `List`\[[ProfilerRuleEvaluationStatusTypeDef](./type_defs.md#profilerruleevaluationstatustypedef)\]
- `ProfilingStatus`: [ProfilingStatusType](./literals.md#profilingstatustype)
- `RetryStrategy`: [RetryStrategyTypeDef](./type_defs.md#retrystrategytypedef)
- `Environment`: `Dict`\[`str`, `str`\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetransformjobrequestrequesttypedef"></a>

## DescribeTransformJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTransformJobRequestRequestTypeDef
```

Required fields:

- `TransformJobName`: `str`

<a id="describetransformjobresponsetypedef"></a>

## DescribeTransformJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTransformJobResponseTypeDef
```

Required fields:

- `TransformJobName`: `str`
- `TransformJobArn`: `str`
- `TransformJobStatus`:
  [TransformJobStatusType](./literals.md#transformjobstatustype)
- `FailureReason`: `str`
- `ModelName`: `str`
- `MaxConcurrentTransforms`: `int`
- `ModelClientConfig`:
  [ModelClientConfigTypeDef](./type_defs.md#modelclientconfigtypedef)
- `MaxPayloadInMB`: `int`
- `BatchStrategy`: [BatchStrategyType](./literals.md#batchstrategytype)
- `Environment`: `Dict`\[`str`, `str`\]
- `TransformInput`:
  [TransformInputTypeDef](./type_defs.md#transforminputtypedef)
- `TransformOutput`:
  [TransformOutputTypeDef](./type_defs.md#transformoutputtypedef)
- `TransformResources`:
  [TransformResourcesTypeDef](./type_defs.md#transformresourcestypedef)
- `CreationTime`: `datetime`
- `TransformStartTime`: `datetime`
- `TransformEndTime`: `datetime`
- `LabelingJobArn`: `str`
- `AutoMLJobArn`: `str`
- `DataProcessing`:
  [DataProcessingTypeDef](./type_defs.md#dataprocessingtypedef)
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetrialcomponentrequestrequesttypedef"></a>

## DescribeTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`

<a id="describetrialcomponentresponsetypedef"></a>

## DescribeTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentName`: `str`
- `TrialComponentArn`: `str`
- `DisplayName`: `str`
- `Source`:
  [TrialComponentSourceTypeDef](./type_defs.md#trialcomponentsourcetypedef)
- `Status`:
  [TrialComponentStatusTypeDef](./type_defs.md#trialcomponentstatustypedef)
- `StartTime`: `datetime`
- `EndTime`: `datetime`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `Parameters`: `Dict`\[`str`,
  [TrialComponentParameterValueTypeDef](./type_defs.md#trialcomponentparametervaluetypedef)\]
- `InputArtifacts`: `Dict`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `OutputArtifacts`: `Dict`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Metrics`:
  `List`\[[TrialComponentMetricSummaryTypeDef](./type_defs.md#trialcomponentmetricsummarytypedef)\]
- `LineageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describetrialrequestrequesttypedef"></a>

## DescribeTrialRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrialRequestRequestTypeDef
```

Required fields:

- `TrialName`: `str`

<a id="describetrialresponsetypedef"></a>

## DescribeTrialResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeTrialResponseTypeDef
```

Required fields:

- `TrialName`: `str`
- `TrialArn`: `str`
- `DisplayName`: `str`
- `ExperimentName`: `str`
- `Source`: [TrialSourceTypeDef](./type_defs.md#trialsourcetypedef)
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeuserprofilerequestrequesttypedef"></a>

## DescribeUserProfileRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeUserProfileRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`

<a id="describeuserprofileresponsetypedef"></a>

## DescribeUserProfileResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeUserProfileResponseTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileArn`: `str`
- `UserProfileName`: `str`
- `HomeEfsFileSystemUid`: `str`
- `Status`: [UserProfileStatusType](./literals.md#userprofilestatustype)
- `LastModifiedTime`: `datetime`
- `CreationTime`: `datetime`
- `FailureReason`: `str`
- `SingleSignOnUserIdentifier`: `str`
- `SingleSignOnUserValue`: `str`
- `UserSettings`: [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeworkforcerequestrequesttypedef"></a>

## DescribeWorkforceRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeWorkforceRequestRequestTypeDef
```

Required fields:

- `WorkforceName`: `str`

<a id="describeworkforceresponsetypedef"></a>

## DescribeWorkforceResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeWorkforceResponseTypeDef
```

Required fields:

- `Workforce`: [WorkforceTypeDef](./type_defs.md#workforcetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="describeworkteamrequestrequesttypedef"></a>

## DescribeWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamName`: `str`

<a id="describeworkteamresponsetypedef"></a>

## DescribeWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DescribeWorkteamResponseTypeDef
```

Required fields:

- `Workteam`: [WorkteamTypeDef](./type_defs.md#workteamtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="desiredweightandcapacitytypedef"></a>

## DesiredWeightAndCapacityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DesiredWeightAndCapacityTypeDef
```

Required fields:

- `VariantName`: `str`

Optional fields:

- `DesiredWeight`: `float`
- `DesiredInstanceCount`: `int`

<a id="devicefleetsummarytypedef"></a>

## DeviceFleetSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeviceFleetSummaryTypeDef
```

Required fields:

- `DeviceFleetArn`: `str`
- `DeviceFleetName`: `str`

Optional fields:

- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="devicestatstypedef"></a>

## DeviceStatsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeviceStatsTypeDef
```

Required fields:

- `ConnectedDeviceCount`: `int`
- `RegisteredDeviceCount`: `int`

<a id="devicesummarytypedef"></a>

## DeviceSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeviceSummaryTypeDef
```

Required fields:

- `DeviceName`: `str`
- `DeviceArn`: `str`

Optional fields:

- `Description`: `str`
- `DeviceFleetName`: `str`
- `IotThingName`: `str`
- `RegistrationTime`: `datetime`
- `LatestHeartbeat`: `datetime`
- `Models`:
  `List`\[[EdgeModelSummaryTypeDef](./type_defs.md#edgemodelsummarytypedef)\]
- `AgentVersion`: `str`

<a id="devicetypedef"></a>

## DeviceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DeviceTypeDef
```

Required fields:

- `DeviceName`: `str`

Optional fields:

- `Description`: `str`
- `IotThingName`: `str`

<a id="disassociatetrialcomponentrequestrequesttypedef"></a>

## DisassociateTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DisassociateTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`
- `TrialName`: `str`

<a id="disassociatetrialcomponentresponsetypedef"></a>

## DisassociateTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DisassociateTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentArn`: `str`
- `TrialArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="domaindetailstypedef"></a>

## DomainDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DomainDetailsTypeDef
```

Optional fields:

- `DomainArn`: `str`
- `DomainId`: `str`
- `DomainName`: `str`
- `Status`: [DomainStatusType](./literals.md#domainstatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `Url`: `str`

<a id="domainsettingsforupdatetypedef"></a>

## DomainSettingsForUpdateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DomainSettingsForUpdateTypeDef
```

Optional fields:

- `RStudioServerProDomainSettingsForUpdate`:
  [RStudioServerProDomainSettingsForUpdateTypeDef](./type_defs.md#rstudioserverprodomainsettingsforupdatetypedef)

<a id="domainsettingstypedef"></a>

## DomainSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DomainSettingsTypeDef
```

Optional fields:

- `SecurityGroupIds`: `Sequence`\[`str`\]
- `RStudioServerProDomainSettings`:
  [RStudioServerProDomainSettingsTypeDef](./type_defs.md#rstudioserverprodomainsettingstypedef)

<a id="driftcheckbaselinestypedef"></a>

## DriftCheckBaselinesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DriftCheckBaselinesTypeDef
```

Optional fields:

- `Bias`: [DriftCheckBiasTypeDef](./type_defs.md#driftcheckbiastypedef)
- `Explainability`:
  [DriftCheckExplainabilityTypeDef](./type_defs.md#driftcheckexplainabilitytypedef)
- `ModelQuality`:
  [DriftCheckModelQualityTypeDef](./type_defs.md#driftcheckmodelqualitytypedef)
- `ModelDataQuality`:
  [DriftCheckModelDataQualityTypeDef](./type_defs.md#driftcheckmodeldataqualitytypedef)

<a id="driftcheckbiastypedef"></a>

## DriftCheckBiasTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DriftCheckBiasTypeDef
```

Optional fields:

- `ConfigFile`: [FileSourceTypeDef](./type_defs.md#filesourcetypedef)
- `PreTrainingConstraints`:
  [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `PostTrainingConstraints`:
  [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="driftcheckexplainabilitytypedef"></a>

## DriftCheckExplainabilityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DriftCheckExplainabilityTypeDef
```

Optional fields:

- `Constraints`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `ConfigFile`: [FileSourceTypeDef](./type_defs.md#filesourcetypedef)

<a id="driftcheckmodeldataqualitytypedef"></a>

## DriftCheckModelDataQualityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DriftCheckModelDataQualityTypeDef
```

Optional fields:

- `Statistics`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `Constraints`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="driftcheckmodelqualitytypedef"></a>

## DriftCheckModelQualityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import DriftCheckModelQualityTypeDef
```

Optional fields:

- `Statistics`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `Constraints`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="emrstepmetadatatypedef"></a>

## EMRStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EMRStepMetadataTypeDef
```

Optional fields:

- `ClusterId`: `str`
- `StepId`: `str`
- `StepName`: `str`
- `LogFilePath`: `str`

<a id="edgemodelstattypedef"></a>

## EdgeModelStatTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgeModelStatTypeDef
```

Required fields:

- `ModelName`: `str`
- `ModelVersion`: `str`
- `OfflineDeviceCount`: `int`
- `ConnectedDeviceCount`: `int`
- `ActiveDeviceCount`: `int`
- `SamplingDeviceCount`: `int`

<a id="edgemodelsummarytypedef"></a>

## EdgeModelSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgeModelSummaryTypeDef
```

Required fields:

- `ModelName`: `str`
- `ModelVersion`: `str`

<a id="edgemodeltypedef"></a>

## EdgeModelTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgeModelTypeDef
```

Required fields:

- `ModelName`: `str`
- `ModelVersion`: `str`

Optional fields:

- `LatestSampleTime`: `datetime`
- `LatestInference`: `datetime`

<a id="edgeoutputconfigtypedef"></a>

## EdgeOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgeOutputConfigTypeDef
```

Required fields:

- `S3OutputLocation`: `str`

Optional fields:

- `KmsKeyId`: `str`
- `PresetDeploymentType`: `Literal['GreengrassV2Component']` (see
  [EdgePresetDeploymentTypeType](./literals.md#edgepresetdeploymenttypetype))
- `PresetDeploymentConfig`: `str`

<a id="edgepackagingjobsummarytypedef"></a>

## EdgePackagingJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgePackagingJobSummaryTypeDef
```

Required fields:

- `EdgePackagingJobArn`: `str`
- `EdgePackagingJobName`: `str`
- `EdgePackagingJobStatus`:
  [EdgePackagingJobStatusType](./literals.md#edgepackagingjobstatustype)

Optional fields:

- `CompilationJobName`: `str`
- `ModelName`: `str`
- `ModelVersion`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="edgepresetdeploymentoutputtypedef"></a>

## EdgePresetDeploymentOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgePresetDeploymentOutputTypeDef
```

Required fields:

- `Type`: `Literal['GreengrassV2Component']` (see
  [EdgePresetDeploymentTypeType](./literals.md#edgepresetdeploymenttypetype))

Optional fields:

- `Artifact`: `str`
- `Status`:
  [EdgePresetDeploymentStatusType](./literals.md#edgepresetdeploymentstatustype)
- `StatusMessage`: `str`

<a id="edgetypedef"></a>

## EdgeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EdgeTypeDef
```

Optional fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`
- `AssociationType`:
  [AssociationEdgeTypeType](./literals.md#associationedgetypetype)

<a id="endpointconfigsummarytypedef"></a>

## EndpointConfigSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointConfigSummaryTypeDef
```

Required fields:

- `EndpointConfigName`: `str`
- `EndpointConfigArn`: `str`
- `CreationTime`: `datetime`

<a id="endpointinputconfigurationtypedef"></a>

## EndpointInputConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointInputConfigurationTypeDef
```

Required fields:

- `InstanceType`:
  [ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)

Optional fields:

- `InferenceSpecificationName`: `str`
- `EnvironmentParameterRanges`:
  [EnvironmentParameterRangesTypeDef](./type_defs.md#environmentparameterrangestypedef)

<a id="endpointinputtypedef"></a>

## EndpointInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointInputTypeDef
```

Required fields:

- `EndpointName`: `str`
- `LocalPath`: `str`

Optional fields:

- `S3InputMode`:
  [ProcessingS3InputModeType](./literals.md#processings3inputmodetype)
- `S3DataDistributionType`:
  [ProcessingS3DataDistributionTypeType](./literals.md#processings3datadistributiontypetype)
- `FeaturesAttribute`: `str`
- `InferenceAttribute`: `str`
- `ProbabilityAttribute`: `str`
- `ProbabilityThresholdAttribute`: `float`
- `StartTimeOffset`: `str`
- `EndTimeOffset`: `str`

<a id="endpointoutputconfigurationtypedef"></a>

## EndpointOutputConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointOutputConfigurationTypeDef
```

Required fields:

- `EndpointName`: `str`
- `VariantName`: `str`
- `InstanceType`:
  [ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)
- `InitialInstanceCount`: `int`

<a id="endpointsummarytypedef"></a>

## EndpointSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointSummaryTypeDef
```

Required fields:

- `EndpointName`: `str`
- `EndpointArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `EndpointStatus`: [EndpointStatusType](./literals.md#endpointstatustype)

<a id="endpointtypedef"></a>

## EndpointTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EndpointTypeDef
```

Required fields:

- `EndpointName`: `str`
- `EndpointArn`: `str`
- `EndpointConfigName`: `str`
- `EndpointStatus`: [EndpointStatusType](./literals.md#endpointstatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

Optional fields:

- `ProductionVariants`:
  `List`\[[ProductionVariantSummaryTypeDef](./type_defs.md#productionvariantsummarytypedef)\]
- `DataCaptureConfig`:
  [DataCaptureConfigSummaryTypeDef](./type_defs.md#datacaptureconfigsummarytypedef)
- `FailureReason`: `str`
- `MonitoringSchedules`:
  `List`\[[MonitoringScheduleTypeDef](./type_defs.md#monitoringscheduletypedef)\]
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="environmentparameterrangestypedef"></a>

## EnvironmentParameterRangesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EnvironmentParameterRangesTypeDef
```

Optional fields:

- `CategoricalParameterRanges`:
  `Sequence`\[[CategoricalParameterTypeDef](./type_defs.md#categoricalparametertypedef)\]

<a id="environmentparametertypedef"></a>

## EnvironmentParameterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import EnvironmentParameterTypeDef
```

Required fields:

- `Key`: `str`
- `ValueType`: `str`
- `Value`: `str`

<a id="experimentconfigtypedef"></a>

## ExperimentConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ExperimentConfigTypeDef
```

Optional fields:

- `ExperimentName`: `str`
- `TrialName`: `str`
- `TrialComponentDisplayName`: `str`

<a id="experimentsourcetypedef"></a>

## ExperimentSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ExperimentSourceTypeDef
```

Required fields:

- `SourceArn`: `str`

Optional fields:

- `SourceType`: `str`

<a id="experimentsummarytypedef"></a>

## ExperimentSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ExperimentSummaryTypeDef
```

Optional fields:

- `ExperimentArn`: `str`
- `ExperimentName`: `str`
- `DisplayName`: `str`
- `ExperimentSource`:
  [ExperimentSourceTypeDef](./type_defs.md#experimentsourcetypedef)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="experimenttypedef"></a>

## ExperimentTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ExperimentTypeDef
```

Optional fields:

- `ExperimentName`: `str`
- `ExperimentArn`: `str`
- `DisplayName`: `str`
- `Source`: [ExperimentSourceTypeDef](./type_defs.md#experimentsourcetypedef)
- `Description`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="explainabilitytypedef"></a>

## ExplainabilityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ExplainabilityTypeDef
```

Optional fields:

- `Report`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="failstepmetadatatypedef"></a>

## FailStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FailStepMetadataTypeDef
```

Optional fields:

- `ErrorMessage`: `str`

<a id="featuredefinitiontypedef"></a>

## FeatureDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FeatureDefinitionTypeDef
```

Optional fields:

- `FeatureName`: `str`
- `FeatureType`: [FeatureTypeType](./literals.md#featuretypetype)

<a id="featuregroupsummarytypedef"></a>

## FeatureGroupSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FeatureGroupSummaryTypeDef
```

Required fields:

- `FeatureGroupName`: `str`
- `FeatureGroupArn`: `str`
- `CreationTime`: `datetime`

Optional fields:

- `FeatureGroupStatus`:
  [FeatureGroupStatusType](./literals.md#featuregroupstatustype)
- `OfflineStoreStatus`:
  [OfflineStoreStatusTypeDef](./type_defs.md#offlinestorestatustypedef)

<a id="featuregrouptypedef"></a>

## FeatureGroupTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FeatureGroupTypeDef
```

Optional fields:

- `FeatureGroupArn`: `str`
- `FeatureGroupName`: `str`
- `RecordIdentifierFeatureName`: `str`
- `EventTimeFeatureName`: `str`
- `FeatureDefinitions`:
  `List`\[[FeatureDefinitionTypeDef](./type_defs.md#featuredefinitiontypedef)\]
- `CreationTime`: `datetime`
- `OnlineStoreConfig`:
  [OnlineStoreConfigTypeDef](./type_defs.md#onlinestoreconfigtypedef)
- `OfflineStoreConfig`:
  [OfflineStoreConfigTypeDef](./type_defs.md#offlinestoreconfigtypedef)
- `RoleArn`: `str`
- `FeatureGroupStatus`:
  [FeatureGroupStatusType](./literals.md#featuregroupstatustype)
- `OfflineStoreStatus`:
  [OfflineStoreStatusTypeDef](./type_defs.md#offlinestorestatustypedef)
- `FailureReason`: `str`
- `Description`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="filesourcetypedef"></a>

## FileSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FileSourceTypeDef
```

Required fields:

- `S3Uri`: `str`

Optional fields:

- `ContentType`: `str`
- `ContentDigest`: `str`

<a id="filesystemconfigtypedef"></a>

## FileSystemConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FileSystemConfigTypeDef
```

Optional fields:

- `MountPath`: `str`
- `DefaultUid`: `int`
- `DefaultGid`: `int`

<a id="filesystemdatasourcetypedef"></a>

## FileSystemDataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FileSystemDataSourceTypeDef
```

Required fields:

- `FileSystemId`: `str`
- `FileSystemAccessMode`:
  [FileSystemAccessModeType](./literals.md#filesystemaccessmodetype)
- `FileSystemType`: [FileSystemTypeType](./literals.md#filesystemtypetype)
- `DirectoryPath`: `str`

<a id="filtertypedef"></a>

## FilterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FilterTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `Operator`: [OperatorType](./literals.md#operatortype)
- `Value`: `str`

<a id="finalautomljobobjectivemetrictypedef"></a>

## FinalAutoMLJobObjectiveMetricTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FinalAutoMLJobObjectiveMetricTypeDef
```

Required fields:

- `MetricName`: [AutoMLMetricEnumType](./literals.md#automlmetricenumtype)
- `Value`: `float`

Optional fields:

- `Type`:
  [AutoMLJobObjectiveTypeType](./literals.md#automljobobjectivetypetype)

<a id="finalhyperparametertuningjobobjectivemetrictypedef"></a>

## FinalHyperParameterTuningJobObjectiveMetricTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FinalHyperParameterTuningJobObjectiveMetricTypeDef
```

Required fields:

- `MetricName`: `str`
- `Value`: `float`

Optional fields:

- `Type`:
  [HyperParameterTuningJobObjectiveTypeType](./literals.md#hyperparametertuningjobobjectivetypetype)

<a id="flowdefinitionoutputconfigtypedef"></a>

## FlowDefinitionOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FlowDefinitionOutputConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `KmsKeyId`: `str`

<a id="flowdefinitionsummarytypedef"></a>

## FlowDefinitionSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import FlowDefinitionSummaryTypeDef
```

Required fields:

- `FlowDefinitionName`: `str`
- `FlowDefinitionArn`: `str`
- `FlowDefinitionStatus`:
  [FlowDefinitionStatusType](./literals.md#flowdefinitionstatustype)
- `CreationTime`: `datetime`

Optional fields:

- `FailureReason`: `str`

<a id="getdevicefleetreportrequestrequesttypedef"></a>

## GetDeviceFleetReportRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetDeviceFleetReportRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`

<a id="getdevicefleetreportresponsetypedef"></a>

## GetDeviceFleetReportResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetDeviceFleetReportResponseTypeDef
```

Required fields:

- `DeviceFleetArn`: `str`
- `DeviceFleetName`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)
- `Description`: `str`
- `ReportGenerated`: `datetime`
- `DeviceStats`: [DeviceStatsTypeDef](./type_defs.md#devicestatstypedef)
- `AgentVersions`:
  `List`\[[AgentVersionTypeDef](./type_defs.md#agentversiontypedef)\]
- `ModelStats`:
  `List`\[[EdgeModelStatTypeDef](./type_defs.md#edgemodelstattypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getlineagegrouppolicyrequestrequesttypedef"></a>

## GetLineageGroupPolicyRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetLineageGroupPolicyRequestRequestTypeDef
```

Required fields:

- `LineageGroupName`: `str`

<a id="getlineagegrouppolicyresponsetypedef"></a>

## GetLineageGroupPolicyResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetLineageGroupPolicyResponseTypeDef
```

Required fields:

- `LineageGroupArn`: `str`
- `ResourcePolicy`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getmodelpackagegrouppolicyinputrequesttypedef"></a>

## GetModelPackageGroupPolicyInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetModelPackageGroupPolicyInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`

<a id="getmodelpackagegrouppolicyoutputtypedef"></a>

## GetModelPackageGroupPolicyOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetModelPackageGroupPolicyOutputTypeDef
```

Required fields:

- `ResourcePolicy`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsagemakerservicecatalogportfoliostatusoutputtypedef"></a>

## GetSagemakerServicecatalogPortfolioStatusOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetSagemakerServicecatalogPortfolioStatusOutputTypeDef
```

Required fields:

- `Status`:
  [SagemakerServicecatalogStatusType](./literals.md#sagemakerservicecatalogstatustype)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getsearchsuggestionsrequestrequesttypedef"></a>

## GetSearchSuggestionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetSearchSuggestionsRequestRequestTypeDef
```

Required fields:

- `Resource`: [ResourceTypeType](./literals.md#resourcetypetype)

Optional fields:

- `SuggestionQuery`:
  [SuggestionQueryTypeDef](./type_defs.md#suggestionquerytypedef)

<a id="getsearchsuggestionsresponsetypedef"></a>

## GetSearchSuggestionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GetSearchSuggestionsResponseTypeDef
```

Required fields:

- `PropertyNameSuggestions`:
  `List`\[[PropertyNameSuggestionTypeDef](./type_defs.md#propertynamesuggestiontypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="gitconfigforupdatetypedef"></a>

## GitConfigForUpdateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GitConfigForUpdateTypeDef
```

Optional fields:

- `SecretArn`: `str`

<a id="gitconfigtypedef"></a>

## GitConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import GitConfigTypeDef
```

Required fields:

- `RepositoryUrl`: `str`

Optional fields:

- `Branch`: `str`
- `SecretArn`: `str`

<a id="humanloopactivationconditionsconfigtypedef"></a>

## HumanLoopActivationConditionsConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanLoopActivationConditionsConfigTypeDef
```

Required fields:

- `HumanLoopActivationConditions`: `str`

<a id="humanloopactivationconfigtypedef"></a>

## HumanLoopActivationConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanLoopActivationConfigTypeDef
```

Required fields:

- `HumanLoopActivationConditionsConfig`:
  [HumanLoopActivationConditionsConfigTypeDef](./type_defs.md#humanloopactivationconditionsconfigtypedef)

<a id="humanloopconfigtypedef"></a>

## HumanLoopConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanLoopConfigTypeDef
```

Required fields:

- `WorkteamArn`: `str`
- `HumanTaskUiArn`: `str`
- `TaskTitle`: `str`
- `TaskDescription`: `str`
- `TaskCount`: `int`

Optional fields:

- `TaskAvailabilityLifetimeInSeconds`: `int`
- `TaskTimeLimitInSeconds`: `int`
- `TaskKeywords`: `Sequence`\[`str`\]
- `PublicWorkforceTaskPrice`:
  [PublicWorkforceTaskPriceTypeDef](./type_defs.md#publicworkforcetaskpricetypedef)

<a id="humanlooprequestsourcetypedef"></a>

## HumanLoopRequestSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanLoopRequestSourceTypeDef
```

Required fields:

- `AwsManagedHumanLoopRequestSource`:
  [AwsManagedHumanLoopRequestSourceType](./literals.md#awsmanagedhumanlooprequestsourcetype)

<a id="humantaskconfigtypedef"></a>

## HumanTaskConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanTaskConfigTypeDef
```

Required fields:

- `WorkteamArn`: `str`
- `UiConfig`: [UiConfigTypeDef](./type_defs.md#uiconfigtypedef)
- `PreHumanTaskLambdaArn`: `str`
- `TaskTitle`: `str`
- `TaskDescription`: `str`
- `NumberOfHumanWorkersPerDataObject`: `int`
- `TaskTimeLimitInSeconds`: `int`
- `AnnotationConsolidationConfig`:
  [AnnotationConsolidationConfigTypeDef](./type_defs.md#annotationconsolidationconfigtypedef)

Optional fields:

- `TaskKeywords`: `Sequence`\[`str`\]
- `TaskAvailabilityLifetimeInSeconds`: `int`
- `MaxConcurrentTaskCount`: `int`
- `PublicWorkforceTaskPrice`:
  [PublicWorkforceTaskPriceTypeDef](./type_defs.md#publicworkforcetaskpricetypedef)

<a id="humantaskuisummarytypedef"></a>

## HumanTaskUiSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HumanTaskUiSummaryTypeDef
```

Required fields:

- `HumanTaskUiName`: `str`
- `HumanTaskUiArn`: `str`
- `CreationTime`: `datetime`

<a id="hyperparameteralgorithmspecificationtypedef"></a>

## HyperParameterAlgorithmSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterAlgorithmSpecificationTypeDef
```

Required fields:

- `TrainingInputMode`:
  [TrainingInputModeType](./literals.md#traininginputmodetype)

Optional fields:

- `TrainingImage`: `str`
- `AlgorithmName`: `str`
- `MetricDefinitions`:
  `Sequence`\[[MetricDefinitionTypeDef](./type_defs.md#metricdefinitiontypedef)\]

<a id="hyperparameterspecificationtypedef"></a>

## HyperParameterSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterSpecificationTypeDef
```

Required fields:

- `Name`: `str`
- `Type`: [ParameterTypeType](./literals.md#parametertypetype)

Optional fields:

- `Description`: `str`
- `Range`: [ParameterRangeTypeDef](./type_defs.md#parameterrangetypedef)
- `IsTunable`: `bool`
- `IsRequired`: `bool`
- `DefaultValue`: `str`

<a id="hyperparametertrainingjobdefinitiontypedef"></a>

## HyperParameterTrainingJobDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTrainingJobDefinitionTypeDef
```

Required fields:

- `AlgorithmSpecification`:
  [HyperParameterAlgorithmSpecificationTypeDef](./type_defs.md#hyperparameteralgorithmspecificationtypedef)
- `RoleArn`: `str`
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `ResourceConfig`:
  [ResourceConfigTypeDef](./type_defs.md#resourceconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)

Optional fields:

- `DefinitionName`: `str`
- `TuningObjective`:
  [HyperParameterTuningJobObjectiveTypeDef](./type_defs.md#hyperparametertuningjobobjectivetypedef)
- `HyperParameterRanges`:
  [ParameterRangesTypeDef](./type_defs.md#parameterrangestypedef)
- `StaticHyperParameters`: `Mapping`\[`str`, `str`\]
- `InputDataConfig`:
  `Sequence`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `EnableNetworkIsolation`: `bool`
- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableManagedSpotTraining`: `bool`
- `CheckpointConfig`:
  [CheckpointConfigTypeDef](./type_defs.md#checkpointconfigtypedef)
- `RetryStrategy`: [RetryStrategyTypeDef](./type_defs.md#retrystrategytypedef)

<a id="hyperparametertrainingjobsummarytypedef"></a>

## HyperParameterTrainingJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTrainingJobSummaryTypeDef
```

Required fields:

- `TrainingJobName`: `str`
- `TrainingJobArn`: `str`
- `CreationTime`: `datetime`
- `TrainingJobStatus`:
  [TrainingJobStatusType](./literals.md#trainingjobstatustype)
- `TunedHyperParameters`: `Dict`\[`str`, `str`\]

Optional fields:

- `TrainingJobDefinitionName`: `str`
- `TuningJobName`: `str`
- `TrainingStartTime`: `datetime`
- `TrainingEndTime`: `datetime`
- `FailureReason`: `str`
- `FinalHyperParameterTuningJobObjectiveMetric`:
  [FinalHyperParameterTuningJobObjectiveMetricTypeDef](./type_defs.md#finalhyperparametertuningjobobjectivemetrictypedef)
- `ObjectiveStatus`: [ObjectiveStatusType](./literals.md#objectivestatustype)

<a id="hyperparametertuningjobconfigtypedef"></a>

## HyperParameterTuningJobConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTuningJobConfigTypeDef
```

Required fields:

- `Strategy`:
  [HyperParameterTuningJobStrategyTypeType](./literals.md#hyperparametertuningjobstrategytypetype)
- `ResourceLimits`:
  [ResourceLimitsTypeDef](./type_defs.md#resourcelimitstypedef)

Optional fields:

- `HyperParameterTuningJobObjective`:
  [HyperParameterTuningJobObjectiveTypeDef](./type_defs.md#hyperparametertuningjobobjectivetypedef)
- `ParameterRanges`:
  [ParameterRangesTypeDef](./type_defs.md#parameterrangestypedef)
- `TrainingJobEarlyStoppingType`:
  [TrainingJobEarlyStoppingTypeType](./literals.md#trainingjobearlystoppingtypetype)
- `TuningJobCompletionCriteria`:
  [TuningJobCompletionCriteriaTypeDef](./type_defs.md#tuningjobcompletioncriteriatypedef)

<a id="hyperparametertuningjobobjectivetypedef"></a>

## HyperParameterTuningJobObjectiveTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTuningJobObjectiveTypeDef
```

Required fields:

- `Type`:
  [HyperParameterTuningJobObjectiveTypeType](./literals.md#hyperparametertuningjobobjectivetypetype)
- `MetricName`: `str`

<a id="hyperparametertuningjobsummarytypedef"></a>

## HyperParameterTuningJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTuningJobSummaryTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`
- `HyperParameterTuningJobArn`: `str`
- `HyperParameterTuningJobStatus`:
  [HyperParameterTuningJobStatusType](./literals.md#hyperparametertuningjobstatustype)
- `Strategy`:
  [HyperParameterTuningJobStrategyTypeType](./literals.md#hyperparametertuningjobstrategytypetype)
- `CreationTime`: `datetime`
- `TrainingJobStatusCounters`:
  [TrainingJobStatusCountersTypeDef](./type_defs.md#trainingjobstatuscounterstypedef)
- `ObjectiveStatusCounters`:
  [ObjectiveStatusCountersTypeDef](./type_defs.md#objectivestatuscounterstypedef)

Optional fields:

- `HyperParameterTuningEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `ResourceLimits`:
  [ResourceLimitsTypeDef](./type_defs.md#resourcelimitstypedef)

<a id="hyperparametertuningjobwarmstartconfigtypedef"></a>

## HyperParameterTuningJobWarmStartConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import HyperParameterTuningJobWarmStartConfigTypeDef
```

Required fields:

- `ParentHyperParameterTuningJobs`:
  `Sequence`\[[ParentHyperParameterTuningJobTypeDef](./type_defs.md#parenthyperparametertuningjobtypedef)\]
- `WarmStartType`:
  [HyperParameterTuningJobWarmStartTypeType](./literals.md#hyperparametertuningjobwarmstarttypetype)

<a id="imageconfigtypedef"></a>

## ImageConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ImageConfigTypeDef
```

Required fields:

- `RepositoryAccessMode`:
  [RepositoryAccessModeType](./literals.md#repositoryaccessmodetype)

Optional fields:

- `RepositoryAuthConfig`:
  [RepositoryAuthConfigTypeDef](./type_defs.md#repositoryauthconfigtypedef)

<a id="imagetypedef"></a>

## ImageTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ImageTypeDef
```

Required fields:

- `CreationTime`: `datetime`
- `ImageArn`: `str`
- `ImageName`: `str`
- `ImageStatus`: [ImageStatusType](./literals.md#imagestatustype)
- `LastModifiedTime`: `datetime`

Optional fields:

- `Description`: `str`
- `DisplayName`: `str`
- `FailureReason`: `str`

<a id="imageversiontypedef"></a>

## ImageVersionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ImageVersionTypeDef
```

Required fields:

- `CreationTime`: `datetime`
- `ImageArn`: `str`
- `ImageVersionArn`: `str`
- `ImageVersionStatus`:
  [ImageVersionStatusType](./literals.md#imageversionstatustype)
- `LastModifiedTime`: `datetime`
- `Version`: `int`

Optional fields:

- `FailureReason`: `str`

<a id="inferenceexecutionconfigtypedef"></a>

## InferenceExecutionConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import InferenceExecutionConfigTypeDef
```

Required fields:

- `Mode`:
  [InferenceExecutionModeType](./literals.md#inferenceexecutionmodetype)

<a id="inferencerecommendationtypedef"></a>

## InferenceRecommendationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import InferenceRecommendationTypeDef
```

Required fields:

- `Metrics`:
  [RecommendationMetricsTypeDef](./type_defs.md#recommendationmetricstypedef)
- `EndpointConfiguration`:
  [EndpointOutputConfigurationTypeDef](./type_defs.md#endpointoutputconfigurationtypedef)
- `ModelConfiguration`:
  [ModelConfigurationTypeDef](./type_defs.md#modelconfigurationtypedef)

<a id="inferencerecommendationsjobtypedef"></a>

## InferenceRecommendationsJobTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import InferenceRecommendationsJobTypeDef
```

Required fields:

- `JobName`: `str`
- `JobDescription`: `str`
- `JobType`:
  [RecommendationJobTypeType](./literals.md#recommendationjobtypetype)
- `JobArn`: `str`
- `Status`:
  [RecommendationJobStatusType](./literals.md#recommendationjobstatustype)
- `CreationTime`: `datetime`
- `RoleArn`: `str`
- `LastModifiedTime`: `datetime`

Optional fields:

- `CompletionTime`: `datetime`
- `FailureReason`: `str`

<a id="inferencespecificationtypedef"></a>

## InferenceSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import InferenceSpecificationTypeDef
```

Required fields:

- `Containers`:
  `List`\[[ModelPackageContainerDefinitionTypeDef](./type_defs.md#modelpackagecontainerdefinitiontypedef)\]
- `SupportedContentTypes`: `List`\[`str`\]
- `SupportedResponseMIMETypes`: `List`\[`str`\]

Optional fields:

- `SupportedTransformInstanceTypes`:
  `List`\[[TransformInstanceTypeType](./literals.md#transforminstancetypetype)\]
- `SupportedRealtimeInferenceInstanceTypes`:
  `List`\[[ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)\]

<a id="inputconfigtypedef"></a>

## InputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import InputConfigTypeDef
```

Required fields:

- `S3Uri`: `str`
- `DataInputConfig`: `str`
- `Framework`: [FrameworkType](./literals.md#frameworktype)

Optional fields:

- `FrameworkVersion`: `str`

<a id="integerparameterrangespecificationtypedef"></a>

## IntegerParameterRangeSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import IntegerParameterRangeSpecificationTypeDef
```

Required fields:

- `MinValue`: `str`
- `MaxValue`: `str`

<a id="integerparameterrangetypedef"></a>

## IntegerParameterRangeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import IntegerParameterRangeTypeDef
```

Required fields:

- `Name`: `str`
- `MinValue`: `str`
- `MaxValue`: `str`

Optional fields:

- `ScalingType`:
  [HyperParameterScalingTypeType](./literals.md#hyperparameterscalingtypetype)

<a id="jupyterserverappsettingstypedef"></a>

## JupyterServerAppSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import JupyterServerAppSettingsTypeDef
```

Optional fields:

- `DefaultResourceSpec`:
  [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)
- `LifecycleConfigArns`: `Sequence`\[`str`\]

<a id="kernelgatewayappsettingstypedef"></a>

## KernelGatewayAppSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import KernelGatewayAppSettingsTypeDef
```

Optional fields:

- `DefaultResourceSpec`:
  [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)
- `CustomImages`:
  `Sequence`\[[CustomImageTypeDef](./type_defs.md#customimagetypedef)\]
- `LifecycleConfigArns`: `Sequence`\[`str`\]

<a id="kernelgatewayimageconfigtypedef"></a>

## KernelGatewayImageConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import KernelGatewayImageConfigTypeDef
```

Required fields:

- `KernelSpecs`:
  `Sequence`\[[KernelSpecTypeDef](./type_defs.md#kernelspectypedef)\]

Optional fields:

- `FileSystemConfig`:
  [FileSystemConfigTypeDef](./type_defs.md#filesystemconfigtypedef)

<a id="kernelspectypedef"></a>

## KernelSpecTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import KernelSpecTypeDef
```

Required fields:

- `Name`: `str`

Optional fields:

- `DisplayName`: `str`

<a id="labelcountersforworkteamtypedef"></a>

## LabelCountersForWorkteamTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelCountersForWorkteamTypeDef
```

Optional fields:

- `HumanLabeled`: `int`
- `PendingHuman`: `int`
- `Total`: `int`

<a id="labelcounterstypedef"></a>

## LabelCountersTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelCountersTypeDef
```

Optional fields:

- `TotalLabeled`: `int`
- `HumanLabeled`: `int`
- `MachineLabeled`: `int`
- `FailedNonRetryableError`: `int`
- `Unlabeled`: `int`

<a id="labelingjobalgorithmsconfigtypedef"></a>

## LabelingJobAlgorithmsConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobAlgorithmsConfigTypeDef
```

Required fields:

- `LabelingJobAlgorithmSpecificationArn`: `str`

Optional fields:

- `InitialActiveLearningModelArn`: `str`
- `LabelingJobResourceConfig`:
  [LabelingJobResourceConfigTypeDef](./type_defs.md#labelingjobresourceconfigtypedef)

<a id="labelingjobdataattributestypedef"></a>

## LabelingJobDataAttributesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobDataAttributesTypeDef
```

Optional fields:

- `ContentClassifiers`:
  `Sequence`\[[ContentClassifierType](./literals.md#contentclassifiertype)\]

<a id="labelingjobdatasourcetypedef"></a>

## LabelingJobDataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobDataSourceTypeDef
```

Optional fields:

- `S3DataSource`:
  [LabelingJobS3DataSourceTypeDef](./type_defs.md#labelingjobs3datasourcetypedef)
- `SnsDataSource`:
  [LabelingJobSnsDataSourceTypeDef](./type_defs.md#labelingjobsnsdatasourcetypedef)

<a id="labelingjobforworkteamsummarytypedef"></a>

## LabelingJobForWorkteamSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobForWorkteamSummaryTypeDef
```

Required fields:

- `JobReferenceCode`: `str`
- `WorkRequesterAccountId`: `str`
- `CreationTime`: `datetime`

Optional fields:

- `LabelingJobName`: `str`
- `LabelCounters`:
  [LabelCountersForWorkteamTypeDef](./type_defs.md#labelcountersforworkteamtypedef)
- `NumberOfHumanWorkersPerDataObject`: `int`

<a id="labelingjobinputconfigtypedef"></a>

## LabelingJobInputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobInputConfigTypeDef
```

Required fields:

- `DataSource`:
  [LabelingJobDataSourceTypeDef](./type_defs.md#labelingjobdatasourcetypedef)

Optional fields:

- `DataAttributes`:
  [LabelingJobDataAttributesTypeDef](./type_defs.md#labelingjobdataattributestypedef)

<a id="labelingjoboutputconfigtypedef"></a>

## LabelingJobOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobOutputConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `KmsKeyId`: `str`
- `SnsTopicArn`: `str`

<a id="labelingjoboutputtypedef"></a>

## LabelingJobOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobOutputTypeDef
```

Required fields:

- `OutputDatasetS3Uri`: `str`

Optional fields:

- `FinalActiveLearningModelArn`: `str`

<a id="labelingjobresourceconfigtypedef"></a>

## LabelingJobResourceConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobResourceConfigTypeDef
```

Optional fields:

- `VolumeKmsKeyId`: `str`

<a id="labelingjobs3datasourcetypedef"></a>

## LabelingJobS3DataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobS3DataSourceTypeDef
```

Required fields:

- `ManifestS3Uri`: `str`

<a id="labelingjobsnsdatasourcetypedef"></a>

## LabelingJobSnsDataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobSnsDataSourceTypeDef
```

Required fields:

- `SnsTopicArn`: `str`

<a id="labelingjobstoppingconditionstypedef"></a>

## LabelingJobStoppingConditionsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobStoppingConditionsTypeDef
```

Optional fields:

- `MaxHumanLabeledObjectCount`: `int`
- `MaxPercentageOfInputDatasetLabeled`: `int`

<a id="labelingjobsummarytypedef"></a>

## LabelingJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LabelingJobSummaryTypeDef
```

Required fields:

- `LabelingJobName`: `str`
- `LabelingJobArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LabelingJobStatus`:
  [LabelingJobStatusType](./literals.md#labelingjobstatustype)
- `LabelCounters`: [LabelCountersTypeDef](./type_defs.md#labelcounterstypedef)
- `WorkteamArn`: `str`
- `PreHumanTaskLambdaArn`: `str`

Optional fields:

- `AnnotationConsolidationLambdaArn`: `str`
- `FailureReason`: `str`
- `LabelingJobOutput`:
  [LabelingJobOutputTypeDef](./type_defs.md#labelingjoboutputtypedef)
- `InputConfig`:
  [LabelingJobInputConfigTypeDef](./type_defs.md#labelingjobinputconfigtypedef)

<a id="lambdastepmetadatatypedef"></a>

## LambdaStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LambdaStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`
- `OutputParameters`:
  `List`\[[OutputParameterTypeDef](./type_defs.md#outputparametertypedef)\]

<a id="lineagegroupsummarytypedef"></a>

## LineageGroupSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import LineageGroupSummaryTypeDef
```

Optional fields:

- `LineageGroupArn`: `str`
- `LineageGroupName`: `str`
- `DisplayName`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="listactionsrequestrequesttypedef"></a>

## ListActionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListActionsRequestRequestTypeDef
```

Optional fields:

- `SourceUri`: `str`
- `ActionType`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortActionsByType](./literals.md#sortactionsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listactionsresponsetypedef"></a>

## ListActionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListActionsResponseTypeDef
```

Required fields:

- `ActionSummaries`:
  `List`\[[ActionSummaryTypeDef](./type_defs.md#actionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listalgorithmsinputrequesttypedef"></a>

## ListAlgorithmsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAlgorithmsInputRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `NextToken`: `str`
- `SortBy`: [AlgorithmSortByType](./literals.md#algorithmsortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listalgorithmsoutputtypedef"></a>

## ListAlgorithmsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAlgorithmsOutputTypeDef
```

Required fields:

- `AlgorithmSummaryList`:
  `List`\[[AlgorithmSummaryTypeDef](./type_defs.md#algorithmsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listappimageconfigsrequestrequesttypedef"></a>

## ListAppImageConfigsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAppImageConfigsRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `ModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `ModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `SortBy`:
  [AppImageConfigSortKeyType](./literals.md#appimageconfigsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listappimageconfigsresponsetypedef"></a>

## ListAppImageConfigsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAppImageConfigsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `AppImageConfigs`:
  `List`\[[AppImageConfigDetailsTypeDef](./type_defs.md#appimageconfigdetailstypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listappsrequestrequesttypedef"></a>

## ListAppsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAppsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `SortBy`: `Literal['CreationTime']` (see
  [AppSortKeyType](./literals.md#appsortkeytype))
- `DomainIdEquals`: `str`
- `UserProfileNameEquals`: `str`

<a id="listappsresponsetypedef"></a>

## ListAppsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAppsResponseTypeDef
```

Required fields:

- `Apps`: `List`\[[AppDetailsTypeDef](./type_defs.md#appdetailstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listartifactsrequestrequesttypedef"></a>

## ListArtifactsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListArtifactsRequestRequestTypeDef
```

Optional fields:

- `SourceUri`: `str`
- `ArtifactType`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: `Literal['CreationTime']` (see
  [SortArtifactsByType](./literals.md#sortartifactsbytype))
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listartifactsresponsetypedef"></a>

## ListArtifactsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListArtifactsResponseTypeDef
```

Required fields:

- `ArtifactSummaries`:
  `List`\[[ArtifactSummaryTypeDef](./type_defs.md#artifactsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listassociationsrequestrequesttypedef"></a>

## ListAssociationsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAssociationsRequestRequestTypeDef
```

Optional fields:

- `SourceArn`: `str`
- `DestinationArn`: `str`
- `SourceType`: `str`
- `DestinationType`: `str`
- `AssociationType`:
  [AssociationEdgeTypeType](./literals.md#associationedgetypetype)
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortAssociationsByType](./literals.md#sortassociationsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listassociationsresponsetypedef"></a>

## ListAssociationsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAssociationsResponseTypeDef
```

Required fields:

- `AssociationSummaries`:
  `List`\[[AssociationSummaryTypeDef](./type_defs.md#associationsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listautomljobsrequestrequesttypedef"></a>

## ListAutoMLJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAutoMLJobsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`: [AutoMLJobStatusType](./literals.md#automljobstatustype)
- `SortOrder`: [AutoMLSortOrderType](./literals.md#automlsortordertype)
- `SortBy`: [AutoMLSortByType](./literals.md#automlsortbytype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listautomljobsresponsetypedef"></a>

## ListAutoMLJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListAutoMLJobsResponseTypeDef
```

Required fields:

- `AutoMLJobSummaries`:
  `List`\[[AutoMLJobSummaryTypeDef](./type_defs.md#automljobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcandidatesforautomljobrequestrequesttypedef"></a>

## ListCandidatesForAutoMLJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCandidatesForAutoMLJobRequestRequestTypeDef
```

Required fields:

- `AutoMLJobName`: `str`

Optional fields:

- `StatusEquals`: [CandidateStatusType](./literals.md#candidatestatustype)
- `CandidateNameEquals`: `str`
- `SortOrder`: [AutoMLSortOrderType](./literals.md#automlsortordertype)
- `SortBy`: [CandidateSortByType](./literals.md#candidatesortbytype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listcandidatesforautomljobresponsetypedef"></a>

## ListCandidatesForAutoMLJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCandidatesForAutoMLJobResponseTypeDef
```

Required fields:

- `Candidates`:
  `List`\[[AutoMLCandidateTypeDef](./type_defs.md#automlcandidatetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcoderepositoriesinputrequesttypedef"></a>

## ListCodeRepositoriesInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCodeRepositoriesInputRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `NextToken`: `str`
- `SortBy`: [CodeRepositorySortByType](./literals.md#coderepositorysortbytype)
- `SortOrder`:
  [CodeRepositorySortOrderType](./literals.md#coderepositorysortordertype)

<a id="listcoderepositoriesoutputtypedef"></a>

## ListCodeRepositoriesOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCodeRepositoriesOutputTypeDef
```

Required fields:

- `CodeRepositorySummaryList`:
  `List`\[[CodeRepositorySummaryTypeDef](./type_defs.md#coderepositorysummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcompilationjobsrequestrequesttypedef"></a>

## ListCompilationJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCompilationJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`:
  [CompilationJobStatusType](./literals.md#compilationjobstatustype)
- `SortBy`:
  [ListCompilationJobsSortByType](./literals.md#listcompilationjobssortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listcompilationjobsresponsetypedef"></a>

## ListCompilationJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListCompilationJobsResponseTypeDef
```

Required fields:

- `CompilationJobSummaries`:
  `List`\[[CompilationJobSummaryTypeDef](./type_defs.md#compilationjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listcontextsrequestrequesttypedef"></a>

## ListContextsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListContextsRequestRequestTypeDef
```

Optional fields:

- `SourceUri`: `str`
- `ContextType`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortContextsByType](./literals.md#sortcontextsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listcontextsresponsetypedef"></a>

## ListContextsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListContextsResponseTypeDef
```

Required fields:

- `ContextSummaries`:
  `List`\[[ContextSummaryTypeDef](./type_defs.md#contextsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdataqualityjobdefinitionsrequestrequesttypedef"></a>

## ListDataQualityJobDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDataQualityJobDefinitionsRequestRequestTypeDef
```

Optional fields:

- `EndpointName`: `str`
- `SortBy`:
  [MonitoringJobDefinitionSortKeyType](./literals.md#monitoringjobdefinitionsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listdataqualityjobdefinitionsresponsetypedef"></a>

## ListDataQualityJobDefinitionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDataQualityJobDefinitionsResponseTypeDef
```

Required fields:

- `JobDefinitionSummaries`:
  `List`\[[MonitoringJobDefinitionSummaryTypeDef](./type_defs.md#monitoringjobdefinitionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdevicefleetsrequestrequesttypedef"></a>

## ListDeviceFleetsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDeviceFleetsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `SortBy`:
  [ListDeviceFleetsSortByType](./literals.md#listdevicefleetssortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listdevicefleetsresponsetypedef"></a>

## ListDeviceFleetsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDeviceFleetsResponseTypeDef
```

Required fields:

- `DeviceFleetSummaries`:
  `List`\[[DeviceFleetSummaryTypeDef](./type_defs.md#devicefleetsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdevicesrequestrequesttypedef"></a>

## ListDevicesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDevicesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `LatestHeartbeatAfter`: `Union`\[`datetime`, `str`\]
- `ModelName`: `str`
- `DeviceFleetName`: `str`

<a id="listdevicesresponsetypedef"></a>

## ListDevicesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDevicesResponseTypeDef
```

Required fields:

- `DeviceSummaries`:
  `List`\[[DeviceSummaryTypeDef](./type_defs.md#devicesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listdomainsrequestrequesttypedef"></a>

## ListDomainsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDomainsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listdomainsresponsetypedef"></a>

## ListDomainsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListDomainsResponseTypeDef
```

Required fields:

- `Domains`:
  `List`\[[DomainDetailsTypeDef](./type_defs.md#domaindetailstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listedgepackagingjobsrequestrequesttypedef"></a>

## ListEdgePackagingJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEdgePackagingJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `ModelNameContains`: `str`
- `StatusEquals`:
  [EdgePackagingJobStatusType](./literals.md#edgepackagingjobstatustype)
- `SortBy`:
  [ListEdgePackagingJobsSortByType](./literals.md#listedgepackagingjobssortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listedgepackagingjobsresponsetypedef"></a>

## ListEdgePackagingJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEdgePackagingJobsResponseTypeDef
```

Required fields:

- `EdgePackagingJobSummaries`:
  `List`\[[EdgePackagingJobSummaryTypeDef](./type_defs.md#edgepackagingjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listendpointconfigsinputrequesttypedef"></a>

## ListEndpointConfigsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEndpointConfigsInputRequestTypeDef
```

Optional fields:

- `SortBy`:
  [EndpointConfigSortKeyType](./literals.md#endpointconfigsortkeytype)
- `SortOrder`: [OrderKeyType](./literals.md#orderkeytype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listendpointconfigsoutputtypedef"></a>

## ListEndpointConfigsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEndpointConfigsOutputTypeDef
```

Required fields:

- `EndpointConfigs`:
  `List`\[[EndpointConfigSummaryTypeDef](./type_defs.md#endpointconfigsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listendpointsinputrequesttypedef"></a>

## ListEndpointsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEndpointsInputRequestTypeDef
```

Optional fields:

- `SortBy`: [EndpointSortKeyType](./literals.md#endpointsortkeytype)
- `SortOrder`: [OrderKeyType](./literals.md#orderkeytype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `StatusEquals`: [EndpointStatusType](./literals.md#endpointstatustype)

<a id="listendpointsoutputtypedef"></a>

## ListEndpointsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListEndpointsOutputTypeDef
```

Required fields:

- `Endpoints`:
  `List`\[[EndpointSummaryTypeDef](./type_defs.md#endpointsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listexperimentsrequestrequesttypedef"></a>

## ListExperimentsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListExperimentsRequestRequestTypeDef
```

Optional fields:

- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortExperimentsByType](./literals.md#sortexperimentsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listexperimentsresponsetypedef"></a>

## ListExperimentsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListExperimentsResponseTypeDef
```

Required fields:

- `ExperimentSummaries`:
  `List`\[[ExperimentSummaryTypeDef](./type_defs.md#experimentsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listfeaturegroupsrequestrequesttypedef"></a>

## ListFeatureGroupsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListFeatureGroupsRequestRequestTypeDef
```

Optional fields:

- `NameContains`: `str`
- `FeatureGroupStatusEquals`:
  [FeatureGroupStatusType](./literals.md#featuregroupstatustype)
- `OfflineStoreStatusEquals`:
  [OfflineStoreStatusValueType](./literals.md#offlinestorestatusvaluetype)
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `SortOrder`:
  [FeatureGroupSortOrderType](./literals.md#featuregroupsortordertype)
- `SortBy`: [FeatureGroupSortByType](./literals.md#featuregroupsortbytype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listfeaturegroupsresponsetypedef"></a>

## ListFeatureGroupsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListFeatureGroupsResponseTypeDef
```

Required fields:

- `FeatureGroupSummaries`:
  `List`\[[FeatureGroupSummaryTypeDef](./type_defs.md#featuregroupsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listflowdefinitionsrequestrequesttypedef"></a>

## ListFlowDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListFlowDefinitionsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listflowdefinitionsresponsetypedef"></a>

## ListFlowDefinitionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListFlowDefinitionsResponseTypeDef
```

Required fields:

- `FlowDefinitionSummaries`:
  `List`\[[FlowDefinitionSummaryTypeDef](./type_defs.md#flowdefinitionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listhumantaskuisrequestrequesttypedef"></a>

## ListHumanTaskUisRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListHumanTaskUisRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listhumantaskuisresponsetypedef"></a>

## ListHumanTaskUisResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListHumanTaskUisResponseTypeDef
```

Required fields:

- `HumanTaskUiSummaries`:
  `List`\[[HumanTaskUiSummaryTypeDef](./type_defs.md#humantaskuisummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listhyperparametertuningjobsrequestrequesttypedef"></a>

## ListHyperParameterTuningJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListHyperParameterTuningJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `SortBy`:
  [HyperParameterTuningJobSortByOptionsType](./literals.md#hyperparametertuningjobsortbyoptionstype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NameContains`: `str`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `StatusEquals`:
  [HyperParameterTuningJobStatusType](./literals.md#hyperparametertuningjobstatustype)

<a id="listhyperparametertuningjobsresponsetypedef"></a>

## ListHyperParameterTuningJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListHyperParameterTuningJobsResponseTypeDef
```

Required fields:

- `HyperParameterTuningJobSummaries`:
  `List`\[[HyperParameterTuningJobSummaryTypeDef](./type_defs.md#hyperparametertuningjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listimageversionsrequestrequesttypedef"></a>

## ListImageVersionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListImageVersionsRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `SortBy`: [ImageVersionSortByType](./literals.md#imageversionsortbytype)
- `SortOrder`:
  [ImageVersionSortOrderType](./literals.md#imageversionsortordertype)

<a id="listimageversionsresponsetypedef"></a>

## ListImageVersionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListImageVersionsResponseTypeDef
```

Required fields:

- `ImageVersions`:
  `List`\[[ImageVersionTypeDef](./type_defs.md#imageversiontypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listimagesrequestrequesttypedef"></a>

## ListImagesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListImagesRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `NextToken`: `str`
- `SortBy`: [ImageSortByType](./literals.md#imagesortbytype)
- `SortOrder`: [ImageSortOrderType](./literals.md#imagesortordertype)

<a id="listimagesresponsetypedef"></a>

## ListImagesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListImagesResponseTypeDef
```

Required fields:

- `Images`: `List`\[[ImageTypeDef](./type_defs.md#imagetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listinferencerecommendationsjobsrequestrequesttypedef"></a>

## ListInferenceRecommendationsJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListInferenceRecommendationsJobsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`:
  [RecommendationJobStatusType](./literals.md#recommendationjobstatustype)
- `SortBy`:
  [ListInferenceRecommendationsJobsSortByType](./literals.md#listinferencerecommendationsjobssortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listinferencerecommendationsjobsresponsetypedef"></a>

## ListInferenceRecommendationsJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListInferenceRecommendationsJobsResponseTypeDef
```

Required fields:

- `InferenceRecommendationsJobs`:
  `List`\[[InferenceRecommendationsJobTypeDef](./type_defs.md#inferencerecommendationsjobtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listlabelingjobsforworkteamrequestrequesttypedef"></a>

## ListLabelingJobsForWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLabelingJobsForWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamArn`: `str`

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `JobReferenceCodeContains`: `str`
- `SortBy`: `Literal['CreationTime']` (see
  [ListLabelingJobsForWorkteamSortByOptionsType](./literals.md#listlabelingjobsforworkteamsortbyoptionstype))
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listlabelingjobsforworkteamresponsetypedef"></a>

## ListLabelingJobsForWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLabelingJobsForWorkteamResponseTypeDef
```

Required fields:

- `LabelingJobSummaryList`:
  `List`\[[LabelingJobForWorkteamSummaryTypeDef](./type_defs.md#labelingjobforworkteamsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listlabelingjobsrequestrequesttypedef"></a>

## ListLabelingJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLabelingJobsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `NameContains`: `str`
- `SortBy`: [SortByType](./literals.md#sortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `StatusEquals`: [LabelingJobStatusType](./literals.md#labelingjobstatustype)

<a id="listlabelingjobsresponsetypedef"></a>

## ListLabelingJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLabelingJobsResponseTypeDef
```

Required fields:

- `LabelingJobSummaryList`:
  `List`\[[LabelingJobSummaryTypeDef](./type_defs.md#labelingjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listlineagegroupsrequestrequesttypedef"></a>

## ListLineageGroupsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLineageGroupsRequestRequestTypeDef
```

Optional fields:

- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortLineageGroupsByType](./literals.md#sortlineagegroupsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listlineagegroupsresponsetypedef"></a>

## ListLineageGroupsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListLineageGroupsResponseTypeDef
```

Required fields:

- `LineageGroupSummaries`:
  `List`\[[LineageGroupSummaryTypeDef](./type_defs.md#lineagegroupsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelbiasjobdefinitionsrequestrequesttypedef"></a>

## ListModelBiasJobDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelBiasJobDefinitionsRequestRequestTypeDef
```

Optional fields:

- `EndpointName`: `str`
- `SortBy`:
  [MonitoringJobDefinitionSortKeyType](./literals.md#monitoringjobdefinitionsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listmodelbiasjobdefinitionsresponsetypedef"></a>

## ListModelBiasJobDefinitionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelBiasJobDefinitionsResponseTypeDef
```

Required fields:

- `JobDefinitionSummaries`:
  `List`\[[MonitoringJobDefinitionSummaryTypeDef](./type_defs.md#monitoringjobdefinitionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelexplainabilityjobdefinitionsrequestrequesttypedef"></a>

## ListModelExplainabilityJobDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelExplainabilityJobDefinitionsRequestRequestTypeDef
```

Optional fields:

- `EndpointName`: `str`
- `SortBy`:
  [MonitoringJobDefinitionSortKeyType](./literals.md#monitoringjobdefinitionsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listmodelexplainabilityjobdefinitionsresponsetypedef"></a>

## ListModelExplainabilityJobDefinitionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelExplainabilityJobDefinitionsResponseTypeDef
```

Required fields:

- `JobDefinitionSummaries`:
  `List`\[[MonitoringJobDefinitionSummaryTypeDef](./type_defs.md#monitoringjobdefinitionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelmetadatarequestrequesttypedef"></a>

## ListModelMetadataRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelMetadataRequestRequestTypeDef
```

Optional fields:

- `SearchExpression`:
  [ModelMetadataSearchExpressionTypeDef](./type_defs.md#modelmetadatasearchexpressiontypedef)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listmodelmetadataresponsetypedef"></a>

## ListModelMetadataResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelMetadataResponseTypeDef
```

Required fields:

- `ModelMetadataSummaries`:
  `List`\[[ModelMetadataSummaryTypeDef](./type_defs.md#modelmetadatasummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelpackagegroupsinputrequesttypedef"></a>

## ListModelPackageGroupsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelPackageGroupsInputRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `NextToken`: `str`
- `SortBy`:
  [ModelPackageGroupSortByType](./literals.md#modelpackagegroupsortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listmodelpackagegroupsoutputtypedef"></a>

## ListModelPackageGroupsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelPackageGroupsOutputTypeDef
```

Required fields:

- `ModelPackageGroupSummaryList`:
  `List`\[[ModelPackageGroupSummaryTypeDef](./type_defs.md#modelpackagegroupsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelpackagesinputrequesttypedef"></a>

## ListModelPackagesInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelPackagesInputRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)
- `ModelPackageGroupName`: `str`
- `ModelPackageType`:
  [ModelPackageTypeType](./literals.md#modelpackagetypetype)
- `NextToken`: `str`
- `SortBy`: [ModelPackageSortByType](./literals.md#modelpackagesortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listmodelpackagesoutputtypedef"></a>

## ListModelPackagesOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelPackagesOutputTypeDef
```

Required fields:

- `ModelPackageSummaryList`:
  `List`\[[ModelPackageSummaryTypeDef](./type_defs.md#modelpackagesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelqualityjobdefinitionsrequestrequesttypedef"></a>

## ListModelQualityJobDefinitionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelQualityJobDefinitionsRequestRequestTypeDef
```

Optional fields:

- `EndpointName`: `str`
- `SortBy`:
  [MonitoringJobDefinitionSortKeyType](./literals.md#monitoringjobdefinitionsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listmodelqualityjobdefinitionsresponsetypedef"></a>

## ListModelQualityJobDefinitionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelQualityJobDefinitionsResponseTypeDef
```

Required fields:

- `JobDefinitionSummaries`:
  `List`\[[MonitoringJobDefinitionSummaryTypeDef](./type_defs.md#monitoringjobdefinitionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmodelsinputrequesttypedef"></a>

## ListModelsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelsInputRequestTypeDef
```

Optional fields:

- `SortBy`: [ModelSortKeyType](./literals.md#modelsortkeytype)
- `SortOrder`: [OrderKeyType](./literals.md#orderkeytype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listmodelsoutputtypedef"></a>

## ListModelsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListModelsOutputTypeDef
```

Required fields:

- `Models`: `List`\[[ModelSummaryTypeDef](./type_defs.md#modelsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmonitoringexecutionsrequestrequesttypedef"></a>

## ListMonitoringExecutionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListMonitoringExecutionsRequestRequestTypeDef
```

Optional fields:

- `MonitoringScheduleName`: `str`
- `EndpointName`: `str`
- `SortBy`:
  [MonitoringExecutionSortKeyType](./literals.md#monitoringexecutionsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `ScheduledTimeBefore`: `Union`\[`datetime`, `str`\]
- `ScheduledTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `StatusEquals`: [ExecutionStatusType](./literals.md#executionstatustype)
- `MonitoringJobDefinitionName`: `str`
- `MonitoringTypeEquals`:
  [MonitoringTypeType](./literals.md#monitoringtypetype)

<a id="listmonitoringexecutionsresponsetypedef"></a>

## ListMonitoringExecutionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListMonitoringExecutionsResponseTypeDef
```

Required fields:

- `MonitoringExecutionSummaries`:
  `List`\[[MonitoringExecutionSummaryTypeDef](./type_defs.md#monitoringexecutionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listmonitoringschedulesrequestrequesttypedef"></a>

## ListMonitoringSchedulesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListMonitoringSchedulesRequestRequestTypeDef
```

Optional fields:

- `EndpointName`: `str`
- `SortBy`:
  [MonitoringScheduleSortKeyType](./literals.md#monitoringschedulesortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `StatusEquals`: [ScheduleStatusType](./literals.md#schedulestatustype)
- `MonitoringJobDefinitionName`: `str`
- `MonitoringTypeEquals`:
  [MonitoringTypeType](./literals.md#monitoringtypetype)

<a id="listmonitoringschedulesresponsetypedef"></a>

## ListMonitoringSchedulesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListMonitoringSchedulesResponseTypeDef
```

Required fields:

- `MonitoringScheduleSummaries`:
  `List`\[[MonitoringScheduleSummaryTypeDef](./type_defs.md#monitoringschedulesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listnotebookinstancelifecycleconfigsinputrequesttypedef"></a>

## ListNotebookInstanceLifecycleConfigsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListNotebookInstanceLifecycleConfigsInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `SortBy`:
  [NotebookInstanceLifecycleConfigSortKeyType](./literals.md#notebookinstancelifecycleconfigsortkeytype)
- `SortOrder`:
  [NotebookInstanceLifecycleConfigSortOrderType](./literals.md#notebookinstancelifecycleconfigsortordertype)
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]

<a id="listnotebookinstancelifecycleconfigsoutputtypedef"></a>

## ListNotebookInstanceLifecycleConfigsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListNotebookInstanceLifecycleConfigsOutputTypeDef
```

Required fields:

- `NextToken`: `str`
- `NotebookInstanceLifecycleConfigs`:
  `List`\[[NotebookInstanceLifecycleConfigSummaryTypeDef](./type_defs.md#notebookinstancelifecycleconfigsummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listnotebookinstancesinputrequesttypedef"></a>

## ListNotebookInstancesInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListNotebookInstancesInputRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `SortBy`:
  [NotebookInstanceSortKeyType](./literals.md#notebookinstancesortkeytype)
- `SortOrder`:
  [NotebookInstanceSortOrderType](./literals.md#notebookinstancesortordertype)
- `NameContains`: `str`
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `StatusEquals`:
  [NotebookInstanceStatusType](./literals.md#notebookinstancestatustype)
- `NotebookInstanceLifecycleConfigNameContains`: `str`
- `DefaultCodeRepositoryContains`: `str`
- `AdditionalCodeRepositoryEquals`: `str`

<a id="listnotebookinstancesoutputtypedef"></a>

## ListNotebookInstancesOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListNotebookInstancesOutputTypeDef
```

Required fields:

- `NextToken`: `str`
- `NotebookInstances`:
  `List`\[[NotebookInstanceSummaryTypeDef](./type_defs.md#notebookinstancesummarytypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpipelineexecutionstepsrequestrequesttypedef"></a>

## ListPipelineExecutionStepsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineExecutionStepsRequestRequestTypeDef
```

Optional fields:

- `PipelineExecutionArn`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listpipelineexecutionstepsresponsetypedef"></a>

## ListPipelineExecutionStepsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineExecutionStepsResponseTypeDef
```

Required fields:

- `PipelineExecutionSteps`:
  `List`\[[PipelineExecutionStepTypeDef](./type_defs.md#pipelineexecutionsteptypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpipelineexecutionsrequestrequesttypedef"></a>

## ListPipelineExecutionsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineExecutionsRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`

Optional fields:

- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`:
  [SortPipelineExecutionsByType](./literals.md#sortpipelineexecutionsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpipelineexecutionsresponsetypedef"></a>

## ListPipelineExecutionsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineExecutionsResponseTypeDef
```

Required fields:

- `PipelineExecutionSummaries`:
  `List`\[[PipelineExecutionSummaryTypeDef](./type_defs.md#pipelineexecutionsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpipelineparametersforexecutionrequestrequesttypedef"></a>

## ListPipelineParametersForExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineParametersForExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpipelineparametersforexecutionresponsetypedef"></a>

## ListPipelineParametersForExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelineParametersForExecutionResponseTypeDef
```

Required fields:

- `PipelineParameters`:
  `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpipelinesrequestrequesttypedef"></a>

## ListPipelinesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelinesRequestRequestTypeDef
```

Optional fields:

- `PipelineNamePrefix`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortPipelinesByType](./literals.md#sortpipelinesbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listpipelinesresponsetypedef"></a>

## ListPipelinesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListPipelinesResponseTypeDef
```

Required fields:

- `PipelineSummaries`:
  `List`\[[PipelineSummaryTypeDef](./type_defs.md#pipelinesummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listprocessingjobsrequestrequesttypedef"></a>

## ListProcessingJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListProcessingJobsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`:
  [ProcessingJobStatusType](./literals.md#processingjobstatustype)
- `SortBy`: [SortByType](./literals.md#sortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listprocessingjobsresponsetypedef"></a>

## ListProcessingJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListProcessingJobsResponseTypeDef
```

Required fields:

- `ProcessingJobSummaries`:
  `List`\[[ProcessingJobSummaryTypeDef](./type_defs.md#processingjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listprojectsinputrequesttypedef"></a>

## ListProjectsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListProjectsInputRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NameContains`: `str`
- `NextToken`: `str`
- `SortBy`: [ProjectSortByType](./literals.md#projectsortbytype)
- `SortOrder`: [ProjectSortOrderType](./literals.md#projectsortordertype)

<a id="listprojectsoutputtypedef"></a>

## ListProjectsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListProjectsOutputTypeDef
```

Required fields:

- `ProjectSummaryList`:
  `List`\[[ProjectSummaryTypeDef](./type_defs.md#projectsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="liststudiolifecycleconfigsrequestrequesttypedef"></a>

## ListStudioLifecycleConfigsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListStudioLifecycleConfigsRequestRequestTypeDef
```

Optional fields:

- `MaxResults`: `int`
- `NextToken`: `str`
- `NameContains`: `str`
- `AppTypeEquals`:
  [StudioLifecycleConfigAppTypeType](./literals.md#studiolifecycleconfigapptypetype)
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `ModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `ModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `SortBy`:
  [StudioLifecycleConfigSortKeyType](./literals.md#studiolifecycleconfigsortkeytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="liststudiolifecycleconfigsresponsetypedef"></a>

## ListStudioLifecycleConfigsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListStudioLifecycleConfigsResponseTypeDef
```

Required fields:

- `NextToken`: `str`
- `StudioLifecycleConfigs`:
  `List`\[[StudioLifecycleConfigDetailsTypeDef](./type_defs.md#studiolifecycleconfigdetailstypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listsubscribedworkteamsrequestrequesttypedef"></a>

## ListSubscribedWorkteamsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListSubscribedWorkteamsRequestRequestTypeDef
```

Optional fields:

- `NameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listsubscribedworkteamsresponsetypedef"></a>

## ListSubscribedWorkteamsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListSubscribedWorkteamsResponseTypeDef
```

Required fields:

- `SubscribedWorkteams`:
  `List`\[[SubscribedWorkteamTypeDef](./type_defs.md#subscribedworkteamtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtagsinputrequesttypedef"></a>

## ListTagsInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTagsInputRequestTypeDef
```

Required fields:

- `ResourceArn`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listtagsoutputtypedef"></a>

## ListTagsOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTagsOutputTypeDef
```

Required fields:

- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtrainingjobsforhyperparametertuningjobrequestrequesttypedef"></a>

## ListTrainingJobsForHyperParameterTuningJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrainingJobsForHyperParameterTuningJobRequestRequestTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `StatusEquals`: [TrainingJobStatusType](./literals.md#trainingjobstatustype)
- `SortBy`:
  [TrainingJobSortByOptionsType](./literals.md#trainingjobsortbyoptionstype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listtrainingjobsforhyperparametertuningjobresponsetypedef"></a>

## ListTrainingJobsForHyperParameterTuningJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrainingJobsForHyperParameterTuningJobResponseTypeDef
```

Required fields:

- `TrainingJobSummaries`:
  `List`\[[HyperParameterTrainingJobSummaryTypeDef](./type_defs.md#hyperparametertrainingjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtrainingjobsrequestrequesttypedef"></a>

## ListTrainingJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrainingJobsRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`: [TrainingJobStatusType](./literals.md#trainingjobstatustype)
- `SortBy`: [SortByType](./literals.md#sortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)

<a id="listtrainingjobsresponsetypedef"></a>

## ListTrainingJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrainingJobsResponseTypeDef
```

Required fields:

- `TrainingJobSummaries`:
  `List`\[[TrainingJobSummaryTypeDef](./type_defs.md#trainingjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtransformjobsrequestrequesttypedef"></a>

## ListTransformJobsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTransformJobsRequestRequestTypeDef
```

Optional fields:

- `CreationTimeAfter`: `Union`\[`datetime`, `str`\]
- `CreationTimeBefore`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeAfter`: `Union`\[`datetime`, `str`\]
- `LastModifiedTimeBefore`: `Union`\[`datetime`, `str`\]
- `NameContains`: `str`
- `StatusEquals`:
  [TransformJobStatusType](./literals.md#transformjobstatustype)
- `SortBy`: [SortByType](./literals.md#sortbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listtransformjobsresponsetypedef"></a>

## ListTransformJobsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTransformJobsResponseTypeDef
```

Required fields:

- `TransformJobSummaries`:
  `List`\[[TransformJobSummaryTypeDef](./type_defs.md#transformjobsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtrialcomponentsrequestrequesttypedef"></a>

## ListTrialComponentsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrialComponentsRequestRequestTypeDef
```

Optional fields:

- `ExperimentName`: `str`
- `TrialName`: `str`
- `SourceArn`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`:
  [SortTrialComponentsByType](./literals.md#sorttrialcomponentsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtrialcomponentsresponsetypedef"></a>

## ListTrialComponentsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrialComponentsResponseTypeDef
```

Required fields:

- `TrialComponentSummaries`:
  `List`\[[TrialComponentSummaryTypeDef](./type_defs.md#trialcomponentsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listtrialsrequestrequesttypedef"></a>

## ListTrialsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrialsRequestRequestTypeDef
```

Optional fields:

- `ExperimentName`: `str`
- `TrialComponentName`: `str`
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `SortBy`: [SortTrialsByType](./literals.md#sorttrialsbytype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="listtrialsresponsetypedef"></a>

## ListTrialsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListTrialsResponseTypeDef
```

Required fields:

- `TrialSummaries`:
  `List`\[[TrialSummaryTypeDef](./type_defs.md#trialsummarytypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listuserprofilesrequestrequesttypedef"></a>

## ListUserProfilesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListUserProfilesRequestRequestTypeDef
```

Optional fields:

- `NextToken`: `str`
- `MaxResults`: `int`
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `SortBy`: [UserProfileSortKeyType](./literals.md#userprofilesortkeytype)
- `DomainIdEquals`: `str`
- `UserProfileNameContains`: `str`

<a id="listuserprofilesresponsetypedef"></a>

## ListUserProfilesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListUserProfilesResponseTypeDef
```

Required fields:

- `UserProfiles`:
  `List`\[[UserProfileDetailsTypeDef](./type_defs.md#userprofiledetailstypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listworkforcesrequestrequesttypedef"></a>

## ListWorkforcesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListWorkforcesRequestRequestTypeDef
```

Optional fields:

- `SortBy`:
  [ListWorkforcesSortByOptionsType](./literals.md#listworkforcessortbyoptionstype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listworkforcesresponsetypedef"></a>

## ListWorkforcesResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListWorkforcesResponseTypeDef
```

Required fields:

- `Workforces`: `List`\[[WorkforceTypeDef](./type_defs.md#workforcetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listworkteamsrequestrequesttypedef"></a>

## ListWorkteamsRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListWorkteamsRequestRequestTypeDef
```

Optional fields:

- `SortBy`:
  [ListWorkteamsSortByOptionsType](./literals.md#listworkteamssortbyoptionstype)
- `SortOrder`: [SortOrderType](./literals.md#sortordertype)
- `NameContains`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="listworkteamsresponsetypedef"></a>

## ListWorkteamsResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ListWorkteamsResponseTypeDef
```

Required fields:

- `Workteams`: `List`\[[WorkteamTypeDef](./type_defs.md#workteamtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="memberdefinitiontypedef"></a>

## MemberDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MemberDefinitionTypeDef
```

Optional fields:

- `CognitoMemberDefinition`:
  [CognitoMemberDefinitionTypeDef](./type_defs.md#cognitomemberdefinitiontypedef)
- `OidcMemberDefinition`:
  [OidcMemberDefinitionTypeDef](./type_defs.md#oidcmemberdefinitiontypedef)

<a id="metadatapropertiestypedef"></a>

## MetadataPropertiesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MetadataPropertiesTypeDef
```

Optional fields:

- `CommitId`: `str`
- `Repository`: `str`
- `GeneratedBy`: `str`
- `ProjectId`: `str`

<a id="metricdatatypedef"></a>

## MetricDataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MetricDataTypeDef
```

Optional fields:

- `MetricName`: `str`
- `Value`: `float`
- `Timestamp`: `datetime`

<a id="metricdatumtypedef"></a>

## MetricDatumTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MetricDatumTypeDef
```

Optional fields:

- `MetricName`: [AutoMLMetricEnumType](./literals.md#automlmetricenumtype)
- `Value`: `float`
- `Set`: [MetricSetSourceType](./literals.md#metricsetsourcetype)

<a id="metricdefinitiontypedef"></a>

## MetricDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MetricDefinitionTypeDef
```

Required fields:

- `Name`: `str`
- `Regex`: `str`

<a id="metricssourcetypedef"></a>

## MetricsSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MetricsSourceTypeDef
```

Required fields:

- `ContentType`: `str`
- `S3Uri`: `str`

Optional fields:

- `ContentDigest`: `str`

<a id="modelartifactstypedef"></a>

## ModelArtifactsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelArtifactsTypeDef
```

Required fields:

- `S3ModelArtifacts`: `str`

<a id="modelbiasappspecificationtypedef"></a>

## ModelBiasAppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelBiasAppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`
- `ConfigUri`: `str`

Optional fields:

- `Environment`: `Mapping`\[`str`, `str`\]

<a id="modelbiasbaselineconfigtypedef"></a>

## ModelBiasBaselineConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelBiasBaselineConfigTypeDef
```

Optional fields:

- `BaseliningJobName`: `str`
- `ConstraintsResource`:
  [MonitoringConstraintsResourceTypeDef](./type_defs.md#monitoringconstraintsresourcetypedef)

<a id="modelbiasjobinputtypedef"></a>

## ModelBiasJobInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelBiasJobInputTypeDef
```

Required fields:

- `EndpointInput`: [EndpointInputTypeDef](./type_defs.md#endpointinputtypedef)
- `GroundTruthS3Input`:
  [MonitoringGroundTruthS3InputTypeDef](./type_defs.md#monitoringgroundtruths3inputtypedef)

<a id="modelclientconfigtypedef"></a>

## ModelClientConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelClientConfigTypeDef
```

Optional fields:

- `InvocationsTimeoutInSeconds`: `int`
- `InvocationsMaxRetries`: `int`

<a id="modelconfigurationtypedef"></a>

## ModelConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelConfigurationTypeDef
```

Optional fields:

- `InferenceSpecificationName`: `str`
- `EnvironmentParameters`:
  `List`\[[EnvironmentParameterTypeDef](./type_defs.md#environmentparametertypedef)\]

<a id="modeldataqualitytypedef"></a>

## ModelDataQualityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelDataQualityTypeDef
```

Optional fields:

- `Statistics`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `Constraints`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="modeldeployconfigtypedef"></a>

## ModelDeployConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelDeployConfigTypeDef
```

Optional fields:

- `AutoGenerateEndpointName`: `bool`
- `EndpointName`: `str`

<a id="modeldeployresulttypedef"></a>

## ModelDeployResultTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelDeployResultTypeDef
```

Optional fields:

- `EndpointName`: `str`

<a id="modeldigeststypedef"></a>

## ModelDigestsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelDigestsTypeDef
```

Optional fields:

- `ArtifactDigest`: `str`

<a id="modelexplainabilityappspecificationtypedef"></a>

## ModelExplainabilityAppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelExplainabilityAppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`
- `ConfigUri`: `str`

Optional fields:

- `Environment`: `Mapping`\[`str`, `str`\]

<a id="modelexplainabilitybaselineconfigtypedef"></a>

## ModelExplainabilityBaselineConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelExplainabilityBaselineConfigTypeDef
```

Optional fields:

- `BaseliningJobName`: `str`
- `ConstraintsResource`:
  [MonitoringConstraintsResourceTypeDef](./type_defs.md#monitoringconstraintsresourcetypedef)

<a id="modelexplainabilityjobinputtypedef"></a>

## ModelExplainabilityJobInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelExplainabilityJobInputTypeDef
```

Required fields:

- `EndpointInput`: [EndpointInputTypeDef](./type_defs.md#endpointinputtypedef)

<a id="modelinputtypedef"></a>

## ModelInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelInputTypeDef
```

Required fields:

- `DataInputConfig`: `str`

<a id="modellatencythresholdtypedef"></a>

## ModelLatencyThresholdTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelLatencyThresholdTypeDef
```

Optional fields:

- `Percentile`: `str`
- `ValueInMilliseconds`: `int`

<a id="modelmetadatafiltertypedef"></a>

## ModelMetadataFilterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelMetadataFilterTypeDef
```

Required fields:

- `Name`:
  [ModelMetadataFilterTypeType](./literals.md#modelmetadatafiltertypetype)
- `Value`: `str`

<a id="modelmetadatasearchexpressiontypedef"></a>

## ModelMetadataSearchExpressionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelMetadataSearchExpressionTypeDef
```

Optional fields:

- `Filters`:
  `Sequence`\[[ModelMetadataFilterTypeDef](./type_defs.md#modelmetadatafiltertypedef)\]

<a id="modelmetadatasummarytypedef"></a>

## ModelMetadataSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelMetadataSummaryTypeDef
```

Required fields:

- `Domain`: `str`
- `Framework`: `str`
- `Task`: `str`
- `Model`: `str`
- `FrameworkVersion`: `str`

<a id="modelmetricstypedef"></a>

## ModelMetricsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelMetricsTypeDef
```

Optional fields:

- `ModelQuality`: [ModelQualityTypeDef](./type_defs.md#modelqualitytypedef)
- `ModelDataQuality`:
  [ModelDataQualityTypeDef](./type_defs.md#modeldataqualitytypedef)
- `Bias`: [BiasTypeDef](./type_defs.md#biastypedef)
- `Explainability`:
  [ExplainabilityTypeDef](./type_defs.md#explainabilitytypedef)

<a id="modelpackagecontainerdefinitiontypedef"></a>

## ModelPackageContainerDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageContainerDefinitionTypeDef
```

Required fields:

- `Image`: `str`

Optional fields:

- `ContainerHostname`: `str`
- `ImageDigest`: `str`
- `ModelDataUrl`: `str`
- `ProductId`: `str`
- `Environment`: `Dict`\[`str`, `str`\]
- `ModelInput`: [ModelInputTypeDef](./type_defs.md#modelinputtypedef)
- `Framework`: `str`
- `FrameworkVersion`: `str`
- `NearestModelName`: `str`

<a id="modelpackagegroupsummarytypedef"></a>

## ModelPackageGroupSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageGroupSummaryTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`
- `ModelPackageGroupArn`: `str`
- `CreationTime`: `datetime`
- `ModelPackageGroupStatus`:
  [ModelPackageGroupStatusType](./literals.md#modelpackagegroupstatustype)

Optional fields:

- `ModelPackageGroupDescription`: `str`

<a id="modelpackagegrouptypedef"></a>

## ModelPackageGroupTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageGroupTypeDef
```

Optional fields:

- `ModelPackageGroupName`: `str`
- `ModelPackageGroupArn`: `str`
- `ModelPackageGroupDescription`: `str`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ModelPackageGroupStatus`:
  [ModelPackageGroupStatusType](./literals.md#modelpackagegroupstatustype)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="modelpackagestatusdetailstypedef"></a>

## ModelPackageStatusDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageStatusDetailsTypeDef
```

Required fields:

- `ValidationStatuses`:
  `List`\[[ModelPackageStatusItemTypeDef](./type_defs.md#modelpackagestatusitemtypedef)\]

Optional fields:

- `ImageScanStatuses`:
  `List`\[[ModelPackageStatusItemTypeDef](./type_defs.md#modelpackagestatusitemtypedef)\]

<a id="modelpackagestatusitemtypedef"></a>

## ModelPackageStatusItemTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageStatusItemTypeDef
```

Required fields:

- `Name`: `str`
- `Status`:
  [DetailedModelPackageStatusType](./literals.md#detailedmodelpackagestatustype)

Optional fields:

- `FailureReason`: `str`

<a id="modelpackagesummarytypedef"></a>

## ModelPackageSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageSummaryTypeDef
```

Required fields:

- `ModelPackageName`: `str`
- `ModelPackageArn`: `str`
- `CreationTime`: `datetime`
- `ModelPackageStatus`:
  [ModelPackageStatusType](./literals.md#modelpackagestatustype)

Optional fields:

- `ModelPackageGroupName`: `str`
- `ModelPackageVersion`: `int`
- `ModelPackageDescription`: `str`
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)

<a id="modelpackagetypedef"></a>

## ModelPackageTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageTypeDef
```

Optional fields:

- `ModelPackageName`: `str`
- `ModelPackageGroupName`: `str`
- `ModelPackageVersion`: `int`
- `ModelPackageArn`: `str`
- `ModelPackageDescription`: `str`
- `CreationTime`: `datetime`
- `InferenceSpecification`:
  [InferenceSpecificationTypeDef](./type_defs.md#inferencespecificationtypedef)
- `SourceAlgorithmSpecification`:
  [SourceAlgorithmSpecificationTypeDef](./type_defs.md#sourcealgorithmspecificationtypedef)
- `ValidationSpecification`:
  [ModelPackageValidationSpecificationTypeDef](./type_defs.md#modelpackagevalidationspecificationtypedef)
- `ModelPackageStatus`:
  [ModelPackageStatusType](./literals.md#modelpackagestatustype)
- `ModelPackageStatusDetails`:
  [ModelPackageStatusDetailsTypeDef](./type_defs.md#modelpackagestatusdetailstypedef)
- `CertifyForMarketplace`: `bool`
- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `ModelMetrics`: [ModelMetricsTypeDef](./type_defs.md#modelmetricstypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ApprovalDescription`: `str`
- `Domain`: `str`
- `Task`: `str`
- `SamplePayloadUrl`: `str`
- `AdditionalInferenceSpecifications`:
  `List`\[[AdditionalInferenceSpecificationDefinitionTypeDef](./type_defs.md#additionalinferencespecificationdefinitiontypedef)\]
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `CustomerMetadataProperties`: `Dict`\[`str`, `str`\]
- `DriftCheckBaselines`:
  [DriftCheckBaselinesTypeDef](./type_defs.md#driftcheckbaselinestypedef)

<a id="modelpackagevalidationprofiletypedef"></a>

## ModelPackageValidationProfileTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageValidationProfileTypeDef
```

Required fields:

- `ProfileName`: `str`
- `TransformJobDefinition`:
  [TransformJobDefinitionTypeDef](./type_defs.md#transformjobdefinitiontypedef)

<a id="modelpackagevalidationspecificationtypedef"></a>

## ModelPackageValidationSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelPackageValidationSpecificationTypeDef
```

Required fields:

- `ValidationRole`: `str`
- `ValidationProfiles`:
  `Sequence`\[[ModelPackageValidationProfileTypeDef](./type_defs.md#modelpackagevalidationprofiletypedef)\]

<a id="modelqualityappspecificationtypedef"></a>

## ModelQualityAppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelQualityAppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`

Optional fields:

- `ContainerEntrypoint`: `Sequence`\[`str`\]
- `ContainerArguments`: `Sequence`\[`str`\]
- `RecordPreprocessorSourceUri`: `str`
- `PostAnalyticsProcessorSourceUri`: `str`
- `ProblemType`:
  [MonitoringProblemTypeType](./literals.md#monitoringproblemtypetype)
- `Environment`: `Mapping`\[`str`, `str`\]

<a id="modelqualitybaselineconfigtypedef"></a>

## ModelQualityBaselineConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelQualityBaselineConfigTypeDef
```

Optional fields:

- `BaseliningJobName`: `str`
- `ConstraintsResource`:
  [MonitoringConstraintsResourceTypeDef](./type_defs.md#monitoringconstraintsresourcetypedef)

<a id="modelqualityjobinputtypedef"></a>

## ModelQualityJobInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelQualityJobInputTypeDef
```

Required fields:

- `EndpointInput`: [EndpointInputTypeDef](./type_defs.md#endpointinputtypedef)
- `GroundTruthS3Input`:
  [MonitoringGroundTruthS3InputTypeDef](./type_defs.md#monitoringgroundtruths3inputtypedef)

<a id="modelqualitytypedef"></a>

## ModelQualityTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelQualityTypeDef
```

Optional fields:

- `Statistics`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)
- `Constraints`: [MetricsSourceTypeDef](./type_defs.md#metricssourcetypedef)

<a id="modelstepmetadatatypedef"></a>

## ModelStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="modelsummarytypedef"></a>

## ModelSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ModelSummaryTypeDef
```

Required fields:

- `ModelName`: `str`
- `ModelArn`: `str`
- `CreationTime`: `datetime`

<a id="monitoringappspecificationtypedef"></a>

## MonitoringAppSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringAppSpecificationTypeDef
```

Required fields:

- `ImageUri`: `str`

Optional fields:

- `ContainerEntrypoint`: `Sequence`\[`str`\]
- `ContainerArguments`: `Sequence`\[`str`\]
- `RecordPreprocessorSourceUri`: `str`
- `PostAnalyticsProcessorSourceUri`: `str`

<a id="monitoringbaselineconfigtypedef"></a>

## MonitoringBaselineConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringBaselineConfigTypeDef
```

Optional fields:

- `BaseliningJobName`: `str`
- `ConstraintsResource`:
  [MonitoringConstraintsResourceTypeDef](./type_defs.md#monitoringconstraintsresourcetypedef)
- `StatisticsResource`:
  [MonitoringStatisticsResourceTypeDef](./type_defs.md#monitoringstatisticsresourcetypedef)

<a id="monitoringclusterconfigtypedef"></a>

## MonitoringClusterConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringClusterConfigTypeDef
```

Required fields:

- `InstanceCount`: `int`
- `InstanceType`:
  [ProcessingInstanceTypeType](./literals.md#processinginstancetypetype)
- `VolumeSizeInGB`: `int`

Optional fields:

- `VolumeKmsKeyId`: `str`

<a id="monitoringconstraintsresourcetypedef"></a>

## MonitoringConstraintsResourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringConstraintsResourceTypeDef
```

Optional fields:

- `S3Uri`: `str`

<a id="monitoringexecutionsummarytypedef"></a>

## MonitoringExecutionSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringExecutionSummaryTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`
- `ScheduledTime`: `datetime`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `MonitoringExecutionStatus`:
  [ExecutionStatusType](./literals.md#executionstatustype)

Optional fields:

- `ProcessingJobArn`: `str`
- `EndpointName`: `str`
- `FailureReason`: `str`
- `MonitoringJobDefinitionName`: `str`
- `MonitoringType`: [MonitoringTypeType](./literals.md#monitoringtypetype)

<a id="monitoringgroundtruths3inputtypedef"></a>

## MonitoringGroundTruthS3InputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringGroundTruthS3InputTypeDef
```

Optional fields:

- `S3Uri`: `str`

<a id="monitoringinputtypedef"></a>

## MonitoringInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringInputTypeDef
```

Required fields:

- `EndpointInput`: [EndpointInputTypeDef](./type_defs.md#endpointinputtypedef)

<a id="monitoringjobdefinitionsummarytypedef"></a>

## MonitoringJobDefinitionSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringJobDefinitionSummaryTypeDef
```

Required fields:

- `MonitoringJobDefinitionName`: `str`
- `MonitoringJobDefinitionArn`: `str`
- `CreationTime`: `datetime`
- `EndpointName`: `str`

<a id="monitoringjobdefinitiontypedef"></a>

## MonitoringJobDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringJobDefinitionTypeDef
```

Required fields:

- `MonitoringInputs`:
  `Sequence`\[[MonitoringInputTypeDef](./type_defs.md#monitoringinputtypedef)\]
- `MonitoringOutputConfig`:
  [MonitoringOutputConfigTypeDef](./type_defs.md#monitoringoutputconfigtypedef)
- `MonitoringResources`:
  [MonitoringResourcesTypeDef](./type_defs.md#monitoringresourcestypedef)
- `MonitoringAppSpecification`:
  [MonitoringAppSpecificationTypeDef](./type_defs.md#monitoringappspecificationtypedef)
- `RoleArn`: `str`

Optional fields:

- `BaselineConfig`:
  [MonitoringBaselineConfigTypeDef](./type_defs.md#monitoringbaselineconfigtypedef)
- `StoppingCondition`:
  [MonitoringStoppingConditionTypeDef](./type_defs.md#monitoringstoppingconditiontypedef)
- `Environment`: `Mapping`\[`str`, `str`\]
- `NetworkConfig`: [NetworkConfigTypeDef](./type_defs.md#networkconfigtypedef)

<a id="monitoringnetworkconfigtypedef"></a>

## MonitoringNetworkConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringNetworkConfigTypeDef
```

Optional fields:

- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableNetworkIsolation`: `bool`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)

<a id="monitoringoutputconfigtypedef"></a>

## MonitoringOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringOutputConfigTypeDef
```

Required fields:

- `MonitoringOutputs`:
  `Sequence`\[[MonitoringOutputTypeDef](./type_defs.md#monitoringoutputtypedef)\]

Optional fields:

- `KmsKeyId`: `str`

<a id="monitoringoutputtypedef"></a>

## MonitoringOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringOutputTypeDef
```

Required fields:

- `S3Output`:
  [MonitoringS3OutputTypeDef](./type_defs.md#monitorings3outputtypedef)

<a id="monitoringresourcestypedef"></a>

## MonitoringResourcesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringResourcesTypeDef
```

Required fields:

- `ClusterConfig`:
  [MonitoringClusterConfigTypeDef](./type_defs.md#monitoringclusterconfigtypedef)

<a id="monitorings3outputtypedef"></a>

## MonitoringS3OutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringS3OutputTypeDef
```

Required fields:

- `S3Uri`: `str`
- `LocalPath`: `str`

Optional fields:

- `S3UploadMode`:
  [ProcessingS3UploadModeType](./literals.md#processings3uploadmodetype)

<a id="monitoringscheduleconfigtypedef"></a>

## MonitoringScheduleConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringScheduleConfigTypeDef
```

Optional fields:

- `ScheduleConfig`:
  [ScheduleConfigTypeDef](./type_defs.md#scheduleconfigtypedef)
- `MonitoringJobDefinition`:
  [MonitoringJobDefinitionTypeDef](./type_defs.md#monitoringjobdefinitiontypedef)
- `MonitoringJobDefinitionName`: `str`
- `MonitoringType`: [MonitoringTypeType](./literals.md#monitoringtypetype)

<a id="monitoringschedulesummarytypedef"></a>

## MonitoringScheduleSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringScheduleSummaryTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`
- `MonitoringScheduleArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `MonitoringScheduleStatus`:
  [ScheduleStatusType](./literals.md#schedulestatustype)

Optional fields:

- `EndpointName`: `str`
- `MonitoringJobDefinitionName`: `str`
- `MonitoringType`: [MonitoringTypeType](./literals.md#monitoringtypetype)

<a id="monitoringscheduletypedef"></a>

## MonitoringScheduleTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringScheduleTypeDef
```

Optional fields:

- `MonitoringScheduleArn`: `str`
- `MonitoringScheduleName`: `str`
- `MonitoringScheduleStatus`:
  [ScheduleStatusType](./literals.md#schedulestatustype)
- `MonitoringType`: [MonitoringTypeType](./literals.md#monitoringtypetype)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `MonitoringScheduleConfig`:
  [MonitoringScheduleConfigTypeDef](./type_defs.md#monitoringscheduleconfigtypedef)
- `EndpointName`: `str`
- `LastMonitoringExecutionSummary`:
  [MonitoringExecutionSummaryTypeDef](./type_defs.md#monitoringexecutionsummarytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="monitoringstatisticsresourcetypedef"></a>

## MonitoringStatisticsResourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringStatisticsResourceTypeDef
```

Optional fields:

- `S3Uri`: `str`

<a id="monitoringstoppingconditiontypedef"></a>

## MonitoringStoppingConditionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MonitoringStoppingConditionTypeDef
```

Required fields:

- `MaxRuntimeInSeconds`: `int`

<a id="multimodelconfigtypedef"></a>

## MultiModelConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import MultiModelConfigTypeDef
```

Optional fields:

- `ModelCacheSetting`:
  [ModelCacheSettingType](./literals.md#modelcachesettingtype)

<a id="neovpcconfigtypedef"></a>

## NeoVpcConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NeoVpcConfigTypeDef
```

Required fields:

- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Subnets`: `Sequence`\[`str`\]

<a id="nestedfilterstypedef"></a>

## NestedFiltersTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NestedFiltersTypeDef
```

Required fields:

- `NestedPropertyName`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

<a id="networkconfigtypedef"></a>

## NetworkConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NetworkConfigTypeDef
```

Optional fields:

- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableNetworkIsolation`: `bool`
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)

<a id="notebookinstancelifecycleconfigsummarytypedef"></a>

## NotebookInstanceLifecycleConfigSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NotebookInstanceLifecycleConfigSummaryTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigName`: `str`
- `NotebookInstanceLifecycleConfigArn`: `str`

Optional fields:

- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="notebookinstancelifecyclehooktypedef"></a>

## NotebookInstanceLifecycleHookTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NotebookInstanceLifecycleHookTypeDef
```

Optional fields:

- `Content`: `str`

<a id="notebookinstancesummarytypedef"></a>

## NotebookInstanceSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NotebookInstanceSummaryTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`
- `NotebookInstanceArn`: `str`

Optional fields:

- `NotebookInstanceStatus`:
  [NotebookInstanceStatusType](./literals.md#notebookinstancestatustype)
- `Url`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `NotebookInstanceLifecycleConfigName`: `str`
- `DefaultCodeRepository`: `str`
- `AdditionalCodeRepositories`: `List`\[`str`\]

<a id="notificationconfigurationtypedef"></a>

## NotificationConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import NotificationConfigurationTypeDef
```

Optional fields:

- `NotificationTopicArn`: `str`

<a id="objectivestatuscounterstypedef"></a>

## ObjectiveStatusCountersTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ObjectiveStatusCountersTypeDef
```

Optional fields:

- `Succeeded`: `int`
- `Pending`: `int`
- `Failed`: `int`

<a id="offlinestoreconfigtypedef"></a>

## OfflineStoreConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OfflineStoreConfigTypeDef
```

Required fields:

- `S3StorageConfig`:
  [S3StorageConfigTypeDef](./type_defs.md#s3storageconfigtypedef)

Optional fields:

- `DisableGlueTableCreation`: `bool`
- `DataCatalogConfig`:
  [DataCatalogConfigTypeDef](./type_defs.md#datacatalogconfigtypedef)

<a id="offlinestorestatustypedef"></a>

## OfflineStoreStatusTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OfflineStoreStatusTypeDef
```

Required fields:

- `Status`:
  [OfflineStoreStatusValueType](./literals.md#offlinestorestatusvaluetype)

Optional fields:

- `BlockedReason`: `str`

<a id="oidcconfigforresponsetypedef"></a>

## OidcConfigForResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OidcConfigForResponseTypeDef
```

Optional fields:

- `ClientId`: `str`
- `Issuer`: `str`
- `AuthorizationEndpoint`: `str`
- `TokenEndpoint`: `str`
- `UserInfoEndpoint`: `str`
- `LogoutEndpoint`: `str`
- `JwksUri`: `str`

<a id="oidcconfigtypedef"></a>

## OidcConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OidcConfigTypeDef
```

Required fields:

- `ClientId`: `str`
- `ClientSecret`: `str`
- `Issuer`: `str`
- `AuthorizationEndpoint`: `str`
- `TokenEndpoint`: `str`
- `UserInfoEndpoint`: `str`
- `LogoutEndpoint`: `str`
- `JwksUri`: `str`

<a id="oidcmemberdefinitiontypedef"></a>

## OidcMemberDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OidcMemberDefinitionTypeDef
```

Required fields:

- `Groups`: `Sequence`\[`str`\]

<a id="onlinestoreconfigtypedef"></a>

## OnlineStoreConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OnlineStoreConfigTypeDef
```

Optional fields:

- `SecurityConfig`:
  [OnlineStoreSecurityConfigTypeDef](./type_defs.md#onlinestoresecurityconfigtypedef)
- `EnableOnlineStore`: `bool`

<a id="onlinestoresecurityconfigtypedef"></a>

## OnlineStoreSecurityConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OnlineStoreSecurityConfigTypeDef
```

Optional fields:

- `KmsKeyId`: `str`

<a id="outputconfigtypedef"></a>

## OutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OutputConfigTypeDef
```

Required fields:

- `S3OutputLocation`: `str`

Optional fields:

- `TargetDevice`: [TargetDeviceType](./literals.md#targetdevicetype)
- `TargetPlatform`:
  [TargetPlatformTypeDef](./type_defs.md#targetplatformtypedef)
- `CompilerOptions`: `str`
- `KmsKeyId`: `str`

<a id="outputdataconfigtypedef"></a>

## OutputDataConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OutputDataConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `KmsKeyId`: `str`

<a id="outputparametertypedef"></a>

## OutputParameterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import OutputParameterTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="parallelismconfigurationtypedef"></a>

## ParallelismConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParallelismConfigurationTypeDef
```

Required fields:

- `MaxParallelExecutionSteps`: `int`

<a id="parameterrangetypedef"></a>

## ParameterRangeTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParameterRangeTypeDef
```

Optional fields:

- `IntegerParameterRangeSpecification`:
  [IntegerParameterRangeSpecificationTypeDef](./type_defs.md#integerparameterrangespecificationtypedef)
- `ContinuousParameterRangeSpecification`:
  [ContinuousParameterRangeSpecificationTypeDef](./type_defs.md#continuousparameterrangespecificationtypedef)
- `CategoricalParameterRangeSpecification`:
  [CategoricalParameterRangeSpecificationTypeDef](./type_defs.md#categoricalparameterrangespecificationtypedef)

<a id="parameterrangestypedef"></a>

## ParameterRangesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParameterRangesTypeDef
```

Optional fields:

- `IntegerParameterRanges`:
  `Sequence`\[[IntegerParameterRangeTypeDef](./type_defs.md#integerparameterrangetypedef)\]
- `ContinuousParameterRanges`:
  `Sequence`\[[ContinuousParameterRangeTypeDef](./type_defs.md#continuousparameterrangetypedef)\]
- `CategoricalParameterRanges`:
  `Sequence`\[[CategoricalParameterRangeTypeDef](./type_defs.md#categoricalparameterrangetypedef)\]

<a id="parametertypedef"></a>

## ParameterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParameterTypeDef
```

Required fields:

- `Name`: `str`
- `Value`: `str`

<a id="parenthyperparametertuningjobtypedef"></a>

## ParentHyperParameterTuningJobTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParentHyperParameterTuningJobTypeDef
```

Optional fields:

- `HyperParameterTuningJobName`: `str`

<a id="parenttypedef"></a>

## ParentTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ParentTypeDef
```

Optional fields:

- `TrialName`: `str`
- `ExperimentName`: `str`

<a id="pendingdeploymentsummarytypedef"></a>

## PendingDeploymentSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PendingDeploymentSummaryTypeDef
```

Required fields:

- `EndpointConfigName`: `str`

Optional fields:

- `ProductionVariants`:
  `List`\[[PendingProductionVariantSummaryTypeDef](./type_defs.md#pendingproductionvariantsummarytypedef)\]
- `StartTime`: `datetime`

<a id="pendingproductionvariantsummarytypedef"></a>

## PendingProductionVariantSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PendingProductionVariantSummaryTypeDef
```

Required fields:

- `VariantName`: `str`

Optional fields:

- `DeployedImages`:
  `List`\[[DeployedImageTypeDef](./type_defs.md#deployedimagetypedef)\]
- `CurrentWeight`: `float`
- `DesiredWeight`: `float`
- `CurrentInstanceCount`: `int`
- `DesiredInstanceCount`: `int`
- `InstanceType`:
  [ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)
- `AcceleratorType`:
  [ProductionVariantAcceleratorTypeType](./literals.md#productionvariantacceleratortypetype)
- `VariantStatus`:
  `List`\[[ProductionVariantStatusTypeDef](./type_defs.md#productionvariantstatustypedef)\]
- `CurrentServerlessConfig`:
  [ProductionVariantServerlessConfigTypeDef](./type_defs.md#productionvariantserverlessconfigtypedef)
- `DesiredServerlessConfig`:
  [ProductionVariantServerlessConfigTypeDef](./type_defs.md#productionvariantserverlessconfigtypedef)

<a id="phasetypedef"></a>

## PhaseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PhaseTypeDef
```

Optional fields:

- `InitialNumberOfUsers`: `int`
- `SpawnRate`: `int`
- `DurationInSeconds`: `int`

<a id="pipelinedefinitions3locationtypedef"></a>

## PipelineDefinitionS3LocationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineDefinitionS3LocationTypeDef
```

Required fields:

- `Bucket`: `str`
- `ObjectKey`: `str`

Optional fields:

- `VersionId`: `str`

<a id="pipelineexecutionstepmetadatatypedef"></a>

## PipelineExecutionStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineExecutionStepMetadataTypeDef
```

Optional fields:

- `TrainingJob`:
  [TrainingJobStepMetadataTypeDef](./type_defs.md#trainingjobstepmetadatatypedef)
- `ProcessingJob`:
  [ProcessingJobStepMetadataTypeDef](./type_defs.md#processingjobstepmetadatatypedef)
- `TransformJob`:
  [TransformJobStepMetadataTypeDef](./type_defs.md#transformjobstepmetadatatypedef)
- `TuningJob`:
  [TuningJobStepMetaDataTypeDef](./type_defs.md#tuningjobstepmetadatatypedef)
- `Model`: [ModelStepMetadataTypeDef](./type_defs.md#modelstepmetadatatypedef)
- `RegisterModel`:
  [RegisterModelStepMetadataTypeDef](./type_defs.md#registermodelstepmetadatatypedef)
- `Condition`:
  [ConditionStepMetadataTypeDef](./type_defs.md#conditionstepmetadatatypedef)
- `Callback`:
  [CallbackStepMetadataTypeDef](./type_defs.md#callbackstepmetadatatypedef)
- `Lambda`:
  [LambdaStepMetadataTypeDef](./type_defs.md#lambdastepmetadatatypedef)
- `QualityCheck`:
  [QualityCheckStepMetadataTypeDef](./type_defs.md#qualitycheckstepmetadatatypedef)
- `ClarifyCheck`:
  [ClarifyCheckStepMetadataTypeDef](./type_defs.md#clarifycheckstepmetadatatypedef)
- `EMR`: [EMRStepMetadataTypeDef](./type_defs.md#emrstepmetadatatypedef)
- `Fail`: [FailStepMetadataTypeDef](./type_defs.md#failstepmetadatatypedef)

<a id="pipelineexecutionsteptypedef"></a>

## PipelineExecutionStepTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineExecutionStepTypeDef
```

Optional fields:

- `StepName`: `str`
- `StepDisplayName`: `str`
- `StepDescription`: `str`
- `StartTime`: `datetime`
- `EndTime`: `datetime`
- `StepStatus`: [StepStatusType](./literals.md#stepstatustype)
- `CacheHitResult`:
  [CacheHitResultTypeDef](./type_defs.md#cachehitresulttypedef)
- `AttemptCount`: `int`
- `FailureReason`: `str`
- `Metadata`:
  [PipelineExecutionStepMetadataTypeDef](./type_defs.md#pipelineexecutionstepmetadatatypedef)

<a id="pipelineexecutionsummarytypedef"></a>

## PipelineExecutionSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineExecutionSummaryTypeDef
```

Optional fields:

- `PipelineExecutionArn`: `str`
- `StartTime`: `datetime`
- `PipelineExecutionStatus`:
  [PipelineExecutionStatusType](./literals.md#pipelineexecutionstatustype)
- `PipelineExecutionDescription`: `str`
- `PipelineExecutionDisplayName`: `str`
- `PipelineExecutionFailureReason`: `str`

<a id="pipelineexecutiontypedef"></a>

## PipelineExecutionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineExecutionTypeDef
```

Optional fields:

- `PipelineArn`: `str`
- `PipelineExecutionArn`: `str`
- `PipelineExecutionDisplayName`: `str`
- `PipelineExecutionStatus`:
  [PipelineExecutionStatusType](./literals.md#pipelineexecutionstatustype)
- `PipelineExecutionDescription`: `str`
- `PipelineExperimentConfig`:
  [PipelineExperimentConfigTypeDef](./type_defs.md#pipelineexperimentconfigtypedef)
- `FailureReason`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)
- `PipelineParameters`:
  `List`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]

<a id="pipelineexperimentconfigtypedef"></a>

## PipelineExperimentConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineExperimentConfigTypeDef
```

Optional fields:

- `ExperimentName`: `str`
- `TrialName`: `str`

<a id="pipelinesummarytypedef"></a>

## PipelineSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineSummaryTypeDef
```

Optional fields:

- `PipelineArn`: `str`
- `PipelineName`: `str`
- `PipelineDisplayName`: `str`
- `PipelineDescription`: `str`
- `RoleArn`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LastExecutionTime`: `datetime`

<a id="pipelinetypedef"></a>

## PipelineTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PipelineTypeDef
```

Optional fields:

- `PipelineArn`: `str`
- `PipelineName`: `str`
- `PipelineDisplayName`: `str`
- `PipelineDescription`: `str`
- `RoleArn`: `str`
- `PipelineStatus`: `Literal['Active']` (see
  [PipelineStatusType](./literals.md#pipelinestatustype))
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `LastRunTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="processingclusterconfigtypedef"></a>

## ProcessingClusterConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingClusterConfigTypeDef
```

Required fields:

- `InstanceCount`: `int`
- `InstanceType`:
  [ProcessingInstanceTypeType](./literals.md#processinginstancetypetype)
- `VolumeSizeInGB`: `int`

Optional fields:

- `VolumeKmsKeyId`: `str`

<a id="processingfeaturestoreoutputtypedef"></a>

## ProcessingFeatureStoreOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingFeatureStoreOutputTypeDef
```

Required fields:

- `FeatureGroupName`: `str`

<a id="processinginputtypedef"></a>

## ProcessingInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingInputTypeDef
```

Required fields:

- `InputName`: `str`

Optional fields:

- `AppManaged`: `bool`
- `S3Input`:
  [ProcessingS3InputTypeDef](./type_defs.md#processings3inputtypedef)
- `DatasetDefinition`:
  [DatasetDefinitionTypeDef](./type_defs.md#datasetdefinitiontypedef)

<a id="processingjobstepmetadatatypedef"></a>

## ProcessingJobStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingJobStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="processingjobsummarytypedef"></a>

## ProcessingJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingJobSummaryTypeDef
```

Required fields:

- `ProcessingJobName`: `str`
- `ProcessingJobArn`: `str`
- `CreationTime`: `datetime`
- `ProcessingJobStatus`:
  [ProcessingJobStatusType](./literals.md#processingjobstatustype)

Optional fields:

- `ProcessingEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`
- `ExitMessage`: `str`

<a id="processingjobtypedef"></a>

## ProcessingJobTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingJobTypeDef
```

Optional fields:

- `ProcessingInputs`:
  `List`\[[ProcessingInputTypeDef](./type_defs.md#processinginputtypedef)\]
- `ProcessingOutputConfig`:
  [ProcessingOutputConfigTypeDef](./type_defs.md#processingoutputconfigtypedef)
- `ProcessingJobName`: `str`
- `ProcessingResources`:
  [ProcessingResourcesTypeDef](./type_defs.md#processingresourcestypedef)
- `StoppingCondition`:
  [ProcessingStoppingConditionTypeDef](./type_defs.md#processingstoppingconditiontypedef)
- `AppSpecification`:
  [AppSpecificationTypeDef](./type_defs.md#appspecificationtypedef)
- `Environment`: `Dict`\[`str`, `str`\]
- `NetworkConfig`: [NetworkConfigTypeDef](./type_defs.md#networkconfigtypedef)
- `RoleArn`: `str`
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `ProcessingJobArn`: `str`
- `ProcessingJobStatus`:
  [ProcessingJobStatusType](./literals.md#processingjobstatustype)
- `ExitMessage`: `str`
- `FailureReason`: `str`
- `ProcessingEndTime`: `datetime`
- `ProcessingStartTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `CreationTime`: `datetime`
- `MonitoringScheduleArn`: `str`
- `AutoMLJobArn`: `str`
- `TrainingJobArn`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="processingoutputconfigtypedef"></a>

## ProcessingOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingOutputConfigTypeDef
```

Required fields:

- `Outputs`:
  `Sequence`\[[ProcessingOutputTypeDef](./type_defs.md#processingoutputtypedef)\]

Optional fields:

- `KmsKeyId`: `str`

<a id="processingoutputtypedef"></a>

## ProcessingOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingOutputTypeDef
```

Required fields:

- `OutputName`: `str`

Optional fields:

- `S3Output`:
  [ProcessingS3OutputTypeDef](./type_defs.md#processings3outputtypedef)
- `FeatureStoreOutput`:
  [ProcessingFeatureStoreOutputTypeDef](./type_defs.md#processingfeaturestoreoutputtypedef)
- `AppManaged`: `bool`

<a id="processingresourcestypedef"></a>

## ProcessingResourcesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingResourcesTypeDef
```

Required fields:

- `ClusterConfig`:
  [ProcessingClusterConfigTypeDef](./type_defs.md#processingclusterconfigtypedef)

<a id="processings3inputtypedef"></a>

## ProcessingS3InputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingS3InputTypeDef
```

Required fields:

- `S3Uri`: `str`
- `S3DataType`:
  [ProcessingS3DataTypeType](./literals.md#processings3datatypetype)

Optional fields:

- `LocalPath`: `str`
- `S3InputMode`:
  [ProcessingS3InputModeType](./literals.md#processings3inputmodetype)
- `S3DataDistributionType`:
  [ProcessingS3DataDistributionTypeType](./literals.md#processings3datadistributiontypetype)
- `S3CompressionType`:
  [ProcessingS3CompressionTypeType](./literals.md#processings3compressiontypetype)

<a id="processings3outputtypedef"></a>

## ProcessingS3OutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingS3OutputTypeDef
```

Required fields:

- `S3Uri`: `str`
- `LocalPath`: `str`
- `S3UploadMode`:
  [ProcessingS3UploadModeType](./literals.md#processings3uploadmodetype)

<a id="processingstoppingconditiontypedef"></a>

## ProcessingStoppingConditionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProcessingStoppingConditionTypeDef
```

Required fields:

- `MaxRuntimeInSeconds`: `int`

<a id="productionvariantcoredumpconfigtypedef"></a>

## ProductionVariantCoreDumpConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProductionVariantCoreDumpConfigTypeDef
```

Required fields:

- `DestinationS3Uri`: `str`

Optional fields:

- `KmsKeyId`: `str`

<a id="productionvariantserverlessconfigtypedef"></a>

## ProductionVariantServerlessConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProductionVariantServerlessConfigTypeDef
```

Required fields:

- `MemorySizeInMB`: `int`
- `MaxConcurrency`: `int`

<a id="productionvariantstatustypedef"></a>

## ProductionVariantStatusTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProductionVariantStatusTypeDef
```

Required fields:

- `Status`: [VariantStatusType](./literals.md#variantstatustype)

Optional fields:

- `StatusMessage`: `str`
- `StartTime`: `datetime`

<a id="productionvariantsummarytypedef"></a>

## ProductionVariantSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProductionVariantSummaryTypeDef
```

Required fields:

- `VariantName`: `str`

Optional fields:

- `DeployedImages`:
  `List`\[[DeployedImageTypeDef](./type_defs.md#deployedimagetypedef)\]
- `CurrentWeight`: `float`
- `DesiredWeight`: `float`
- `CurrentInstanceCount`: `int`
- `DesiredInstanceCount`: `int`
- `VariantStatus`:
  `List`\[[ProductionVariantStatusTypeDef](./type_defs.md#productionvariantstatustypedef)\]
- `CurrentServerlessConfig`:
  [ProductionVariantServerlessConfigTypeDef](./type_defs.md#productionvariantserverlessconfigtypedef)
- `DesiredServerlessConfig`:
  [ProductionVariantServerlessConfigTypeDef](./type_defs.md#productionvariantserverlessconfigtypedef)

<a id="productionvarianttypedef"></a>

## ProductionVariantTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProductionVariantTypeDef
```

Required fields:

- `VariantName`: `str`
- `ModelName`: `str`

Optional fields:

- `InitialInstanceCount`: `int`
- `InstanceType`:
  [ProductionVariantInstanceTypeType](./literals.md#productionvariantinstancetypetype)
- `InitialVariantWeight`: `float`
- `AcceleratorType`:
  [ProductionVariantAcceleratorTypeType](./literals.md#productionvariantacceleratortypetype)
- `CoreDumpConfig`:
  [ProductionVariantCoreDumpConfigTypeDef](./type_defs.md#productionvariantcoredumpconfigtypedef)
- `ServerlessConfig`:
  [ProductionVariantServerlessConfigTypeDef](./type_defs.md#productionvariantserverlessconfigtypedef)

<a id="profilerconfigforupdatetypedef"></a>

## ProfilerConfigForUpdateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProfilerConfigForUpdateTypeDef
```

Optional fields:

- `S3OutputPath`: `str`
- `ProfilingIntervalInMilliseconds`: `int`
- `ProfilingParameters`: `Mapping`\[`str`, `str`\]
- `DisableProfiler`: `bool`

<a id="profilerconfigtypedef"></a>

## ProfilerConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProfilerConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `ProfilingIntervalInMilliseconds`: `int`
- `ProfilingParameters`: `Mapping`\[`str`, `str`\]

<a id="profilerruleconfigurationtypedef"></a>

## ProfilerRuleConfigurationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProfilerRuleConfigurationTypeDef
```

Required fields:

- `RuleConfigurationName`: `str`
- `RuleEvaluatorImage`: `str`

Optional fields:

- `LocalPath`: `str`
- `S3OutputPath`: `str`
- `InstanceType`:
  [ProcessingInstanceTypeType](./literals.md#processinginstancetypetype)
- `VolumeSizeInGB`: `int`
- `RuleParameters`: `Mapping`\[`str`, `str`\]

<a id="profilerruleevaluationstatustypedef"></a>

## ProfilerRuleEvaluationStatusTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProfilerRuleEvaluationStatusTypeDef
```

Optional fields:

- `RuleConfigurationName`: `str`
- `RuleEvaluationJobArn`: `str`
- `RuleEvaluationStatus`:
  [RuleEvaluationStatusType](./literals.md#ruleevaluationstatustype)
- `StatusDetails`: `str`
- `LastModifiedTime`: `datetime`

<a id="projectsummarytypedef"></a>

## ProjectSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProjectSummaryTypeDef
```

Required fields:

- `ProjectName`: `str`
- `ProjectArn`: `str`
- `ProjectId`: `str`
- `CreationTime`: `datetime`
- `ProjectStatus`: [ProjectStatusType](./literals.md#projectstatustype)

Optional fields:

- `ProjectDescription`: `str`

<a id="projecttypedef"></a>

## ProjectTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProjectTypeDef
```

Optional fields:

- `ProjectArn`: `str`
- `ProjectName`: `str`
- `ProjectId`: `str`
- `ProjectDescription`: `str`
- `ServiceCatalogProvisioningDetails`:
  [ServiceCatalogProvisioningDetailsTypeDef](./type_defs.md#servicecatalogprovisioningdetailstypedef)
- `ServiceCatalogProvisionedProductDetails`:
  [ServiceCatalogProvisionedProductDetailsTypeDef](./type_defs.md#servicecatalogprovisionedproductdetailstypedef)
- `ProjectStatus`: [ProjectStatusType](./literals.md#projectstatustype)
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `CreationTime`: `datetime`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)

<a id="propertynamequerytypedef"></a>

## PropertyNameQueryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PropertyNameQueryTypeDef
```

Required fields:

- `PropertyNameHint`: `str`

<a id="propertynamesuggestiontypedef"></a>

## PropertyNameSuggestionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PropertyNameSuggestionTypeDef
```

Optional fields:

- `PropertyName`: `str`

<a id="provisioningparametertypedef"></a>

## ProvisioningParameterTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ProvisioningParameterTypeDef
```

Optional fields:

- `Key`: `str`
- `Value`: `str`

<a id="publicworkforcetaskpricetypedef"></a>

## PublicWorkforceTaskPriceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PublicWorkforceTaskPriceTypeDef
```

Optional fields:

- `AmountInUsd`: [USDTypeDef](./type_defs.md#usdtypedef)

<a id="putmodelpackagegrouppolicyinputrequesttypedef"></a>

## PutModelPackageGroupPolicyInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PutModelPackageGroupPolicyInputRequestTypeDef
```

Required fields:

- `ModelPackageGroupName`: `str`
- `ResourcePolicy`: `str`

<a id="putmodelpackagegrouppolicyoutputtypedef"></a>

## PutModelPackageGroupPolicyOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import PutModelPackageGroupPolicyOutputTypeDef
```

Required fields:

- `ModelPackageGroupArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="qualitycheckstepmetadatatypedef"></a>

## QualityCheckStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import QualityCheckStepMetadataTypeDef
```

Optional fields:

- `CheckType`: `str`
- `BaselineUsedForDriftCheckStatistics`: `str`
- `BaselineUsedForDriftCheckConstraints`: `str`
- `CalculatedBaselineStatistics`: `str`
- `CalculatedBaselineConstraints`: `str`
- `ModelPackageGroupName`: `str`
- `ViolationReport`: `str`
- `CheckJobArn`: `str`
- `SkipCheck`: `bool`
- `RegisterNewBaseline`: `bool`

<a id="queryfilterstypedef"></a>

## QueryFiltersTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import QueryFiltersTypeDef
```

Optional fields:

- `Types`: `Sequence`\[`str`\]
- `LineageTypes`:
  `Sequence`\[[LineageTypeType](./literals.md#lineagetypetype)\]
- `CreatedBefore`: `Union`\[`datetime`, `str`\]
- `CreatedAfter`: `Union`\[`datetime`, `str`\]
- `ModifiedBefore`: `Union`\[`datetime`, `str`\]
- `ModifiedAfter`: `Union`\[`datetime`, `str`\]
- `Properties`: `Mapping`\[`str`, `str`\]

<a id="querylineagerequestrequesttypedef"></a>

## QueryLineageRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import QueryLineageRequestRequestTypeDef
```

Required fields:

- `StartArns`: `Sequence`\[`str`\]

Optional fields:

- `Direction`: [DirectionType](./literals.md#directiontype)
- `IncludeEdges`: `bool`
- `Filters`: [QueryFiltersTypeDef](./type_defs.md#queryfilterstypedef)
- `MaxDepth`: `int`
- `MaxResults`: `int`
- `NextToken`: `str`

<a id="querylineageresponsetypedef"></a>

## QueryLineageResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import QueryLineageResponseTypeDef
```

Required fields:

- `Vertices`: `List`\[[VertexTypeDef](./type_defs.md#vertextypedef)\]
- `Edges`: `List`\[[EdgeTypeDef](./type_defs.md#edgetypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rstudioserverproappsettingstypedef"></a>

## RStudioServerProAppSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RStudioServerProAppSettingsTypeDef
```

Optional fields:

- `AccessStatus`:
  [RStudioServerProAccessStatusType](./literals.md#rstudioserverproaccessstatustype)
- `UserGroup`:
  [RStudioServerProUserGroupType](./literals.md#rstudioserverprousergrouptype)

<a id="rstudioserverprodomainsettingsforupdatetypedef"></a>

## RStudioServerProDomainSettingsForUpdateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RStudioServerProDomainSettingsForUpdateTypeDef
```

Required fields:

- `DomainExecutionRoleArn`: `str`

Optional fields:

- `DefaultResourceSpec`:
  [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)

<a id="rstudioserverprodomainsettingstypedef"></a>

## RStudioServerProDomainSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RStudioServerProDomainSettingsTypeDef
```

Required fields:

- `DomainExecutionRoleArn`: `str`

Optional fields:

- `RStudioConnectUrl`: `str`
- `RStudioPackageManagerUrl`: `str`
- `DefaultResourceSpec`:
  [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)

<a id="recommendationjobinputconfigtypedef"></a>

## RecommendationJobInputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RecommendationJobInputConfigTypeDef
```

Required fields:

- `ModelPackageVersionArn`: `str`

Optional fields:

- `JobDurationInSeconds`: `int`
- `TrafficPattern`:
  [TrafficPatternTypeDef](./type_defs.md#trafficpatterntypedef)
- `ResourceLimit`:
  [RecommendationJobResourceLimitTypeDef](./type_defs.md#recommendationjobresourcelimittypedef)
- `EndpointConfigurations`:
  `Sequence`\[[EndpointInputConfigurationTypeDef](./type_defs.md#endpointinputconfigurationtypedef)\]

<a id="recommendationjobresourcelimittypedef"></a>

## RecommendationJobResourceLimitTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RecommendationJobResourceLimitTypeDef
```

Optional fields:

- `MaxNumberOfTests`: `int`
- `MaxParallelOfTests`: `int`

<a id="recommendationjobstoppingconditionstypedef"></a>

## RecommendationJobStoppingConditionsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RecommendationJobStoppingConditionsTypeDef
```

Optional fields:

- `MaxInvocations`: `int`
- `ModelLatencyThresholds`:
  `Sequence`\[[ModelLatencyThresholdTypeDef](./type_defs.md#modellatencythresholdtypedef)\]

<a id="recommendationmetricstypedef"></a>

## RecommendationMetricsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RecommendationMetricsTypeDef
```

Required fields:

- `CostPerHour`: `float`
- `CostPerInference`: `float`
- `MaxInvocations`: `int`
- `ModelLatency`: `int`

<a id="redshiftdatasetdefinitiontypedef"></a>

## RedshiftDatasetDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RedshiftDatasetDefinitionTypeDef
```

Required fields:

- `ClusterId`: `str`
- `Database`: `str`
- `DbUser`: `str`
- `QueryString`: `str`
- `ClusterRoleArn`: `str`
- `OutputS3Uri`: `str`
- `OutputFormat`:
  [RedshiftResultFormatType](./literals.md#redshiftresultformattype)

Optional fields:

- `KmsKeyId`: `str`
- `OutputCompression`:
  [RedshiftResultCompressionTypeType](./literals.md#redshiftresultcompressiontypetype)

<a id="registerdevicesrequestrequesttypedef"></a>

## RegisterDevicesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RegisterDevicesRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `Devices`: `Sequence`\[[DeviceTypeDef](./type_defs.md#devicetypedef)\]

Optional fields:

- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="registermodelstepmetadatatypedef"></a>

## RegisterModelStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RegisterModelStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="renderuitemplaterequestrequesttypedef"></a>

## RenderUiTemplateRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RenderUiTemplateRequestRequestTypeDef
```

Required fields:

- `Task`: [RenderableTaskTypeDef](./type_defs.md#renderabletasktypedef)
- `RoleArn`: `str`

Optional fields:

- `UiTemplate`: [UiTemplateTypeDef](./type_defs.md#uitemplatetypedef)
- `HumanTaskUiArn`: `str`

<a id="renderuitemplateresponsetypedef"></a>

## RenderUiTemplateResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RenderUiTemplateResponseTypeDef
```

Required fields:

- `RenderedContent`: `str`
- `Errors`:
  `List`\[[RenderingErrorTypeDef](./type_defs.md#renderingerrortypedef)\]
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="renderabletasktypedef"></a>

## RenderableTaskTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RenderableTaskTypeDef
```

Required fields:

- `Input`: `str`

<a id="renderingerrortypedef"></a>

## RenderingErrorTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RenderingErrorTypeDef
```

Required fields:

- `Code`: `str`
- `Message`: `str`

<a id="repositoryauthconfigtypedef"></a>

## RepositoryAuthConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RepositoryAuthConfigTypeDef
```

Required fields:

- `RepositoryCredentialsProviderArn`: `str`

<a id="resolvedattributestypedef"></a>

## ResolvedAttributesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ResolvedAttributesTypeDef
```

Optional fields:

- `AutoMLJobObjective`:
  [AutoMLJobObjectiveTypeDef](./type_defs.md#automljobobjectivetypedef)
- `ProblemType`: [ProblemTypeType](./literals.md#problemtypetype)
- `CompletionCriteria`:
  [AutoMLJobCompletionCriteriaTypeDef](./type_defs.md#automljobcompletioncriteriatypedef)

<a id="resourceconfigtypedef"></a>

## ResourceConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ResourceConfigTypeDef
```

Required fields:

- `InstanceType`:
  [TrainingInstanceTypeType](./literals.md#traininginstancetypetype)
- `InstanceCount`: `int`
- `VolumeSizeInGB`: `int`

Optional fields:

- `VolumeKmsKeyId`: `str`

<a id="resourcelimitstypedef"></a>

## ResourceLimitsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ResourceLimitsTypeDef
```

Required fields:

- `MaxNumberOfTrainingJobs`: `int`
- `MaxParallelTrainingJobs`: `int`

<a id="resourcespectypedef"></a>

## ResourceSpecTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ResourceSpecTypeDef
```

Optional fields:

- `SageMakerImageArn`: `str`
- `SageMakerImageVersionArn`: `str`
- `InstanceType`: [AppInstanceTypeType](./literals.md#appinstancetypetype)
- `LifecycleConfigArn`: `str`

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="retentionpolicytypedef"></a>

## RetentionPolicyTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RetentionPolicyTypeDef
```

Optional fields:

- `HomeEfsFileSystem`: [RetentionTypeType](./literals.md#retentiontypetype)

<a id="retrypipelineexecutionrequestrequesttypedef"></a>

## RetryPipelineExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RetryPipelineExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ClientRequestToken`: `str`

Optional fields:

- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)

<a id="retrypipelineexecutionresponsetypedef"></a>

## RetryPipelineExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RetryPipelineExecutionResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="retrystrategytypedef"></a>

## RetryStrategyTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import RetryStrategyTypeDef
```

Required fields:

- `MaximumRetryAttempts`: `int`

<a id="s3datasourcetypedef"></a>

## S3DataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import S3DataSourceTypeDef
```

Required fields:

- `S3DataType`: [S3DataTypeType](./literals.md#s3datatypetype)
- `S3Uri`: `str`

Optional fields:

- `S3DataDistributionType`:
  [S3DataDistributionType](./literals.md#s3datadistributiontype)
- `AttributeNames`: `Sequence`\[`str`\]

<a id="s3storageconfigtypedef"></a>

## S3StorageConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import S3StorageConfigTypeDef
```

Required fields:

- `S3Uri`: `str`

Optional fields:

- `KmsKeyId`: `str`
- `ResolvedOutputS3Uri`: `str`

<a id="scheduleconfigtypedef"></a>

## ScheduleConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ScheduleConfigTypeDef
```

Required fields:

- `ScheduleExpression`: `str`

<a id="searchexpressiontypedef"></a>

## SearchExpressionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SearchExpressionTypeDef
```

Optional fields:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NestedFilters`:
  `Sequence`\[[NestedFiltersTypeDef](./type_defs.md#nestedfilterstypedef)\]
- `SubExpressions`:
  `Sequence`\[[SearchExpressionTypeDef](./type_defs.md#searchexpressiontypedef)\]
- `Operator`: [BooleanOperatorType](./literals.md#booleanoperatortype)

<a id="searchrecordtypedef"></a>

## SearchRecordTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SearchRecordTypeDef
```

Optional fields:

- `TrainingJob`: [TrainingJobTypeDef](./type_defs.md#trainingjobtypedef)
- `Experiment`: [ExperimentTypeDef](./type_defs.md#experimenttypedef)
- `Trial`: [TrialTypeDef](./type_defs.md#trialtypedef)
- `TrialComponent`:
  [TrialComponentTypeDef](./type_defs.md#trialcomponenttypedef)
- `Endpoint`: [EndpointTypeDef](./type_defs.md#endpointtypedef)
- `ModelPackage`: [ModelPackageTypeDef](./type_defs.md#modelpackagetypedef)
- `ModelPackageGroup`:
  [ModelPackageGroupTypeDef](./type_defs.md#modelpackagegrouptypedef)
- `Pipeline`: [PipelineTypeDef](./type_defs.md#pipelinetypedef)
- `PipelineExecution`:
  [PipelineExecutionTypeDef](./type_defs.md#pipelineexecutiontypedef)
- `FeatureGroup`: [FeatureGroupTypeDef](./type_defs.md#featuregrouptypedef)
- `Project`: [ProjectTypeDef](./type_defs.md#projecttypedef)

<a id="searchrequestrequesttypedef"></a>

## SearchRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SearchRequestRequestTypeDef
```

Required fields:

- `Resource`: [ResourceTypeType](./literals.md#resourcetypetype)

Optional fields:

- `SearchExpression`:
  [SearchExpressionTypeDef](./type_defs.md#searchexpressiontypedef)
- `SortBy`: `str`
- `SortOrder`: [SearchSortOrderType](./literals.md#searchsortordertype)
- `NextToken`: `str`
- `MaxResults`: `int`

<a id="searchresponsetypedef"></a>

## SearchResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SearchResponseTypeDef
```

Required fields:

- `Results`:
  `List`\[[SearchRecordTypeDef](./type_defs.md#searchrecordtypedef)\]
- `NextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="secondarystatustransitiontypedef"></a>

## SecondaryStatusTransitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SecondaryStatusTransitionTypeDef
```

Required fields:

- `Status`: [SecondaryStatusType](./literals.md#secondarystatustype)
- `StartTime`: `datetime`

Optional fields:

- `EndTime`: `datetime`
- `StatusMessage`: `str`

<a id="sendpipelineexecutionstepfailurerequestrequesttypedef"></a>

## SendPipelineExecutionStepFailureRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SendPipelineExecutionStepFailureRequestRequestTypeDef
```

Required fields:

- `CallbackToken`: `str`

Optional fields:

- `FailureReason`: `str`
- `ClientRequestToken`: `str`

<a id="sendpipelineexecutionstepfailureresponsetypedef"></a>

## SendPipelineExecutionStepFailureResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SendPipelineExecutionStepFailureResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="sendpipelineexecutionstepsuccessrequestrequesttypedef"></a>

## SendPipelineExecutionStepSuccessRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SendPipelineExecutionStepSuccessRequestRequestTypeDef
```

Required fields:

- `CallbackToken`: `str`

Optional fields:

- `OutputParameters`:
  `Sequence`\[[OutputParameterTypeDef](./type_defs.md#outputparametertypedef)\]
- `ClientRequestToken`: `str`

<a id="sendpipelineexecutionstepsuccessresponsetypedef"></a>

## SendPipelineExecutionStepSuccessResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SendPipelineExecutionStepSuccessResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="servicecatalogprovisionedproductdetailstypedef"></a>

## ServiceCatalogProvisionedProductDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ServiceCatalogProvisionedProductDetailsTypeDef
```

Optional fields:

- `ProvisionedProductId`: `str`
- `ProvisionedProductStatusMessage`: `str`

<a id="servicecatalogprovisioningdetailstypedef"></a>

## ServiceCatalogProvisioningDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ServiceCatalogProvisioningDetailsTypeDef
```

Required fields:

- `ProductId`: `str`

Optional fields:

- `ProvisioningArtifactId`: `str`
- `PathId`: `str`
- `ProvisioningParameters`:
  `Sequence`\[[ProvisioningParameterTypeDef](./type_defs.md#provisioningparametertypedef)\]

<a id="servicecatalogprovisioningupdatedetailstypedef"></a>

## ServiceCatalogProvisioningUpdateDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ServiceCatalogProvisioningUpdateDetailsTypeDef
```

Optional fields:

- `ProvisioningArtifactId`: `str`
- `ProvisioningParameters`:
  `Sequence`\[[ProvisioningParameterTypeDef](./type_defs.md#provisioningparametertypedef)\]

<a id="sharingsettingstypedef"></a>

## SharingSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SharingSettingsTypeDef
```

Optional fields:

- `NotebookOutputOption`:
  [NotebookOutputOptionType](./literals.md#notebookoutputoptiontype)
- `S3OutputPath`: `str`
- `S3KmsKeyId`: `str`

<a id="shuffleconfigtypedef"></a>

## ShuffleConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import ShuffleConfigTypeDef
```

Required fields:

- `Seed`: `int`

<a id="sourcealgorithmspecificationtypedef"></a>

## SourceAlgorithmSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SourceAlgorithmSpecificationTypeDef
```

Required fields:

- `SourceAlgorithms`:
  `Sequence`\[[SourceAlgorithmTypeDef](./type_defs.md#sourcealgorithmtypedef)\]

<a id="sourcealgorithmtypedef"></a>

## SourceAlgorithmTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SourceAlgorithmTypeDef
```

Required fields:

- `AlgorithmName`: `str`

Optional fields:

- `ModelDataUrl`: `str`

<a id="sourceipconfigtypedef"></a>

## SourceIpConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SourceIpConfigTypeDef
```

Required fields:

- `Cidrs`: `Sequence`\[`str`\]

<a id="startmonitoringschedulerequestrequesttypedef"></a>

## StartMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StartMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`

<a id="startnotebookinstanceinputrequesttypedef"></a>

## StartNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StartNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

<a id="startpipelineexecutionrequestrequesttypedef"></a>

## StartPipelineExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StartPipelineExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`
- `ClientRequestToken`: `str`

Optional fields:

- `PipelineExecutionDisplayName`: `str`
- `PipelineParameters`:
  `Sequence`\[[ParameterTypeDef](./type_defs.md#parametertypedef)\]
- `PipelineExecutionDescription`: `str`
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)

<a id="startpipelineexecutionresponsetypedef"></a>

## StartPipelineExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StartPipelineExecutionResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopautomljobrequestrequesttypedef"></a>

## StopAutoMLJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopAutoMLJobRequestRequestTypeDef
```

Required fields:

- `AutoMLJobName`: `str`

<a id="stopcompilationjobrequestrequesttypedef"></a>

## StopCompilationJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopCompilationJobRequestRequestTypeDef
```

Required fields:

- `CompilationJobName`: `str`

<a id="stopedgepackagingjobrequestrequesttypedef"></a>

## StopEdgePackagingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopEdgePackagingJobRequestRequestTypeDef
```

Required fields:

- `EdgePackagingJobName`: `str`

<a id="stophyperparametertuningjobrequestrequesttypedef"></a>

## StopHyperParameterTuningJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopHyperParameterTuningJobRequestRequestTypeDef
```

Required fields:

- `HyperParameterTuningJobName`: `str`

<a id="stopinferencerecommendationsjobrequestrequesttypedef"></a>

## StopInferenceRecommendationsJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopInferenceRecommendationsJobRequestRequestTypeDef
```

Required fields:

- `JobName`: `str`

<a id="stoplabelingjobrequestrequesttypedef"></a>

## StopLabelingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopLabelingJobRequestRequestTypeDef
```

Required fields:

- `LabelingJobName`: `str`

<a id="stopmonitoringschedulerequestrequesttypedef"></a>

## StopMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`

<a id="stopnotebookinstanceinputrequesttypedef"></a>

## StopNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

<a id="stoppipelineexecutionrequestrequesttypedef"></a>

## StopPipelineExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopPipelineExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ClientRequestToken`: `str`

<a id="stoppipelineexecutionresponsetypedef"></a>

## StopPipelineExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopPipelineExecutionResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="stopprocessingjobrequestrequesttypedef"></a>

## StopProcessingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopProcessingJobRequestRequestTypeDef
```

Required fields:

- `ProcessingJobName`: `str`

<a id="stoptrainingjobrequestrequesttypedef"></a>

## StopTrainingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopTrainingJobRequestRequestTypeDef
```

Required fields:

- `TrainingJobName`: `str`

<a id="stoptransformjobrequestrequesttypedef"></a>

## StopTransformJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StopTransformJobRequestRequestTypeDef
```

Required fields:

- `TransformJobName`: `str`

<a id="stoppingconditiontypedef"></a>

## StoppingConditionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StoppingConditionTypeDef
```

Optional fields:

- `MaxRuntimeInSeconds`: `int`
- `MaxWaitTimeInSeconds`: `int`

<a id="studiolifecycleconfigdetailstypedef"></a>

## StudioLifecycleConfigDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import StudioLifecycleConfigDetailsTypeDef
```

Optional fields:

- `StudioLifecycleConfigArn`: `str`
- `StudioLifecycleConfigName`: `str`
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `StudioLifecycleConfigAppType`:
  [StudioLifecycleConfigAppTypeType](./literals.md#studiolifecycleconfigapptypetype)

<a id="subscribedworkteamtypedef"></a>

## SubscribedWorkteamTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SubscribedWorkteamTypeDef
```

Required fields:

- `WorkteamArn`: `str`

Optional fields:

- `MarketplaceTitle`: `str`
- `SellerName`: `str`
- `MarketplaceDescription`: `str`
- `ListingId`: `str`

<a id="suggestionquerytypedef"></a>

## SuggestionQueryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import SuggestionQueryTypeDef
```

Optional fields:

- `PropertyNameQuery`:
  [PropertyNameQueryTypeDef](./type_defs.md#propertynamequerytypedef)

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TagTypeDef
```

Required fields:

- `Key`: `str`
- `Value`: `str`

<a id="targetplatformtypedef"></a>

## TargetPlatformTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TargetPlatformTypeDef
```

Required fields:

- `Os`: [TargetPlatformOsType](./literals.md#targetplatformostype)
- `Arch`: [TargetPlatformArchType](./literals.md#targetplatformarchtype)

Optional fields:

- `Accelerator`:
  [TargetPlatformAcceleratorType](./literals.md#targetplatformacceleratortype)

<a id="tensorboardappsettingstypedef"></a>

## TensorBoardAppSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TensorBoardAppSettingsTypeDef
```

Optional fields:

- `DefaultResourceSpec`:
  [ResourceSpecTypeDef](./type_defs.md#resourcespectypedef)

<a id="tensorboardoutputconfigtypedef"></a>

## TensorBoardOutputConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TensorBoardOutputConfigTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `LocalPath`: `str`

<a id="trafficpatterntypedef"></a>

## TrafficPatternTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrafficPatternTypeDef
```

Optional fields:

- `TrafficType`: `Literal['PHASES']` (see
  [TrafficTypeType](./literals.md#traffictypetype))
- `Phases`: `Sequence`\[[PhaseTypeDef](./type_defs.md#phasetypedef)\]

<a id="trafficroutingconfigtypedef"></a>

## TrafficRoutingConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrafficRoutingConfigTypeDef
```

Required fields:

- `Type`:
  [TrafficRoutingConfigTypeType](./literals.md#trafficroutingconfigtypetype)
- `WaitIntervalInSeconds`: `int`

Optional fields:

- `CanarySize`: [CapacitySizeTypeDef](./type_defs.md#capacitysizetypedef)
- `LinearStepSize`: [CapacitySizeTypeDef](./type_defs.md#capacitysizetypedef)

<a id="trainingjobdefinitiontypedef"></a>

## TrainingJobDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingJobDefinitionTypeDef
```

Required fields:

- `TrainingInputMode`:
  [TrainingInputModeType](./literals.md#traininginputmodetype)
- `InputDataConfig`:
  `Sequence`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `ResourceConfig`:
  [ResourceConfigTypeDef](./type_defs.md#resourceconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)

Optional fields:

- `HyperParameters`: `Mapping`\[`str`, `str`\]

<a id="trainingjobstatuscounterstypedef"></a>

## TrainingJobStatusCountersTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingJobStatusCountersTypeDef
```

Optional fields:

- `Completed`: `int`
- `InProgress`: `int`
- `RetryableError`: `int`
- `NonRetryableError`: `int`
- `Stopped`: `int`

<a id="trainingjobstepmetadatatypedef"></a>

## TrainingJobStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingJobStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="trainingjobsummarytypedef"></a>

## TrainingJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingJobSummaryTypeDef
```

Required fields:

- `TrainingJobName`: `str`
- `TrainingJobArn`: `str`
- `CreationTime`: `datetime`
- `TrainingJobStatus`:
  [TrainingJobStatusType](./literals.md#trainingjobstatustype)

Optional fields:

- `TrainingEndTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="trainingjobtypedef"></a>

## TrainingJobTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingJobTypeDef
```

Optional fields:

- `TrainingJobName`: `str`
- `TrainingJobArn`: `str`
- `TuningJobArn`: `str`
- `LabelingJobArn`: `str`
- `AutoMLJobArn`: `str`
- `ModelArtifacts`:
  [ModelArtifactsTypeDef](./type_defs.md#modelartifactstypedef)
- `TrainingJobStatus`:
  [TrainingJobStatusType](./literals.md#trainingjobstatustype)
- `SecondaryStatus`: [SecondaryStatusType](./literals.md#secondarystatustype)
- `FailureReason`: `str`
- `HyperParameters`: `Dict`\[`str`, `str`\]
- `AlgorithmSpecification`:
  [AlgorithmSpecificationTypeDef](./type_defs.md#algorithmspecificationtypedef)
- `RoleArn`: `str`
- `InputDataConfig`: `List`\[[ChannelTypeDef](./type_defs.md#channeltypedef)\]
- `OutputDataConfig`:
  [OutputDataConfigTypeDef](./type_defs.md#outputdataconfigtypedef)
- `ResourceConfig`:
  [ResourceConfigTypeDef](./type_defs.md#resourceconfigtypedef)
- `VpcConfig`: [VpcConfigTypeDef](./type_defs.md#vpcconfigtypedef)
- `StoppingCondition`:
  [StoppingConditionTypeDef](./type_defs.md#stoppingconditiontypedef)
- `CreationTime`: `datetime`
- `TrainingStartTime`: `datetime`
- `TrainingEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `SecondaryStatusTransitions`:
  `List`\[[SecondaryStatusTransitionTypeDef](./type_defs.md#secondarystatustransitiontypedef)\]
- `FinalMetricDataList`:
  `List`\[[MetricDataTypeDef](./type_defs.md#metricdatatypedef)\]
- `EnableNetworkIsolation`: `bool`
- `EnableInterContainerTrafficEncryption`: `bool`
- `EnableManagedSpotTraining`: `bool`
- `CheckpointConfig`:
  [CheckpointConfigTypeDef](./type_defs.md#checkpointconfigtypedef)
- `TrainingTimeInSeconds`: `int`
- `BillableTimeInSeconds`: `int`
- `DebugHookConfig`:
  [DebugHookConfigTypeDef](./type_defs.md#debughookconfigtypedef)
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `DebugRuleConfigurations`:
  `List`\[[DebugRuleConfigurationTypeDef](./type_defs.md#debugruleconfigurationtypedef)\]
- `TensorBoardOutputConfig`:
  [TensorBoardOutputConfigTypeDef](./type_defs.md#tensorboardoutputconfigtypedef)
- `DebugRuleEvaluationStatuses`:
  `List`\[[DebugRuleEvaluationStatusTypeDef](./type_defs.md#debugruleevaluationstatustypedef)\]
- `Environment`: `Dict`\[`str`, `str`\]
- `RetryStrategy`: [RetryStrategyTypeDef](./type_defs.md#retrystrategytypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="trainingspecificationtypedef"></a>

## TrainingSpecificationTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrainingSpecificationTypeDef
```

Required fields:

- `TrainingImage`: `str`
- `SupportedTrainingInstanceTypes`:
  `Sequence`\[[TrainingInstanceTypeType](./literals.md#traininginstancetypetype)\]
- `TrainingChannels`:
  `Sequence`\[[ChannelSpecificationTypeDef](./type_defs.md#channelspecificationtypedef)\]

Optional fields:

- `TrainingImageDigest`: `str`
- `SupportedHyperParameters`:
  `Sequence`\[[HyperParameterSpecificationTypeDef](./type_defs.md#hyperparameterspecificationtypedef)\]
- `SupportsDistributedTraining`: `bool`
- `MetricDefinitions`:
  `Sequence`\[[MetricDefinitionTypeDef](./type_defs.md#metricdefinitiontypedef)\]
- `SupportedTuningJobObjectiveMetrics`:
  `Sequence`\[[HyperParameterTuningJobObjectiveTypeDef](./type_defs.md#hyperparametertuningjobobjectivetypedef)\]

<a id="transformdatasourcetypedef"></a>

## TransformDataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformDataSourceTypeDef
```

Required fields:

- `S3DataSource`:
  [TransformS3DataSourceTypeDef](./type_defs.md#transforms3datasourcetypedef)

<a id="transforminputtypedef"></a>

## TransformInputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformInputTypeDef
```

Required fields:

- `DataSource`:
  [TransformDataSourceTypeDef](./type_defs.md#transformdatasourcetypedef)

Optional fields:

- `ContentType`: `str`
- `CompressionType`: [CompressionTypeType](./literals.md#compressiontypetype)
- `SplitType`: [SplitTypeType](./literals.md#splittypetype)

<a id="transformjobdefinitiontypedef"></a>

## TransformJobDefinitionTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformJobDefinitionTypeDef
```

Required fields:

- `TransformInput`:
  [TransformInputTypeDef](./type_defs.md#transforminputtypedef)
- `TransformOutput`:
  [TransformOutputTypeDef](./type_defs.md#transformoutputtypedef)
- `TransformResources`:
  [TransformResourcesTypeDef](./type_defs.md#transformresourcestypedef)

Optional fields:

- `MaxConcurrentTransforms`: `int`
- `MaxPayloadInMB`: `int`
- `BatchStrategy`: [BatchStrategyType](./literals.md#batchstrategytype)
- `Environment`: `Mapping`\[`str`, `str`\]

<a id="transformjobstepmetadatatypedef"></a>

## TransformJobStepMetadataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformJobStepMetadataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="transformjobsummarytypedef"></a>

## TransformJobSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformJobSummaryTypeDef
```

Required fields:

- `TransformJobName`: `str`
- `TransformJobArn`: `str`
- `CreationTime`: `datetime`
- `TransformJobStatus`:
  [TransformJobStatusType](./literals.md#transformjobstatustype)

Optional fields:

- `TransformEndTime`: `datetime`
- `LastModifiedTime`: `datetime`
- `FailureReason`: `str`

<a id="transformjobtypedef"></a>

## TransformJobTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformJobTypeDef
```

Optional fields:

- `TransformJobName`: `str`
- `TransformJobArn`: `str`
- `TransformJobStatus`:
  [TransformJobStatusType](./literals.md#transformjobstatustype)
- `FailureReason`: `str`
- `ModelName`: `str`
- `MaxConcurrentTransforms`: `int`
- `ModelClientConfig`:
  [ModelClientConfigTypeDef](./type_defs.md#modelclientconfigtypedef)
- `MaxPayloadInMB`: `int`
- `BatchStrategy`: [BatchStrategyType](./literals.md#batchstrategytype)
- `Environment`: `Dict`\[`str`, `str`\]
- `TransformInput`:
  [TransformInputTypeDef](./type_defs.md#transforminputtypedef)
- `TransformOutput`:
  [TransformOutputTypeDef](./type_defs.md#transformoutputtypedef)
- `TransformResources`:
  [TransformResourcesTypeDef](./type_defs.md#transformresourcestypedef)
- `CreationTime`: `datetime`
- `TransformStartTime`: `datetime`
- `TransformEndTime`: `datetime`
- `LabelingJobArn`: `str`
- `AutoMLJobArn`: `str`
- `DataProcessing`:
  [DataProcessingTypeDef](./type_defs.md#dataprocessingtypedef)
- `ExperimentConfig`:
  [ExperimentConfigTypeDef](./type_defs.md#experimentconfigtypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="transformoutputtypedef"></a>

## TransformOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformOutputTypeDef
```

Required fields:

- `S3OutputPath`: `str`

Optional fields:

- `Accept`: `str`
- `AssembleWith`: [AssemblyTypeType](./literals.md#assemblytypetype)
- `KmsKeyId`: `str`

<a id="transformresourcestypedef"></a>

## TransformResourcesTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformResourcesTypeDef
```

Required fields:

- `InstanceType`:
  [TransformInstanceTypeType](./literals.md#transforminstancetypetype)
- `InstanceCount`: `int`

Optional fields:

- `VolumeKmsKeyId`: `str`

<a id="transforms3datasourcetypedef"></a>

## TransformS3DataSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TransformS3DataSourceTypeDef
```

Required fields:

- `S3DataType`: [S3DataTypeType](./literals.md#s3datatypetype)
- `S3Uri`: `str`

<a id="trialcomponentartifacttypedef"></a>

## TrialComponentArtifactTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentArtifactTypeDef
```

Required fields:

- `Value`: `str`

Optional fields:

- `MediaType`: `str`

<a id="trialcomponentmetricsummarytypedef"></a>

## TrialComponentMetricSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentMetricSummaryTypeDef
```

Optional fields:

- `MetricName`: `str`
- `SourceArn`: `str`
- `TimeStamp`: `datetime`
- `Max`: `float`
- `Min`: `float`
- `Last`: `float`
- `Count`: `int`
- `Avg`: `float`
- `StdDev`: `float`

<a id="trialcomponentparametervaluetypedef"></a>

## TrialComponentParameterValueTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentParameterValueTypeDef
```

Optional fields:

- `StringValue`: `str`
- `NumberValue`: `float`

<a id="trialcomponentsimplesummarytypedef"></a>

## TrialComponentSimpleSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentSimpleSummaryTypeDef
```

Optional fields:

- `TrialComponentName`: `str`
- `TrialComponentArn`: `str`
- `TrialComponentSource`:
  [TrialComponentSourceTypeDef](./type_defs.md#trialcomponentsourcetypedef)
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)

<a id="trialcomponentsourcedetailtypedef"></a>

## TrialComponentSourceDetailTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentSourceDetailTypeDef
```

Optional fields:

- `SourceArn`: `str`
- `TrainingJob`: [TrainingJobTypeDef](./type_defs.md#trainingjobtypedef)
- `ProcessingJob`: [ProcessingJobTypeDef](./type_defs.md#processingjobtypedef)
- `TransformJob`: [TransformJobTypeDef](./type_defs.md#transformjobtypedef)

<a id="trialcomponentsourcetypedef"></a>

## TrialComponentSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentSourceTypeDef
```

Required fields:

- `SourceArn`: `str`

Optional fields:

- `SourceType`: `str`

<a id="trialcomponentstatustypedef"></a>

## TrialComponentStatusTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentStatusTypeDef
```

Optional fields:

- `PrimaryStatus`:
  [TrialComponentPrimaryStatusType](./literals.md#trialcomponentprimarystatustype)
- `Message`: `str`

<a id="trialcomponentsummarytypedef"></a>

## TrialComponentSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentSummaryTypeDef
```

Optional fields:

- `TrialComponentName`: `str`
- `TrialComponentArn`: `str`
- `DisplayName`: `str`
- `TrialComponentSource`:
  [TrialComponentSourceTypeDef](./type_defs.md#trialcomponentsourcetypedef)
- `Status`:
  [TrialComponentStatusTypeDef](./type_defs.md#trialcomponentstatustypedef)
- `StartTime`: `datetime`
- `EndTime`: `datetime`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)

<a id="trialcomponenttypedef"></a>

## TrialComponentTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialComponentTypeDef
```

Optional fields:

- `TrialComponentName`: `str`
- `DisplayName`: `str`
- `TrialComponentArn`: `str`
- `Source`:
  [TrialComponentSourceTypeDef](./type_defs.md#trialcomponentsourcetypedef)
- `Status`:
  [TrialComponentStatusTypeDef](./type_defs.md#trialcomponentstatustypedef)
- `StartTime`: `datetime`
- `EndTime`: `datetime`
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `Parameters`: `Dict`\[`str`,
  [TrialComponentParameterValueTypeDef](./type_defs.md#trialcomponentparametervaluetypedef)\]
- `InputArtifacts`: `Dict`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `OutputArtifacts`: `Dict`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `Metrics`:
  `List`\[[TrialComponentMetricSummaryTypeDef](./type_defs.md#trialcomponentmetricsummarytypedef)\]
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `SourceDetail`:
  [TrialComponentSourceDetailTypeDef](./type_defs.md#trialcomponentsourcedetailtypedef)
- `LineageGroupArn`: `str`
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `Parents`: `List`\[[ParentTypeDef](./type_defs.md#parenttypedef)\]

<a id="trialsourcetypedef"></a>

## TrialSourceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialSourceTypeDef
```

Required fields:

- `SourceArn`: `str`

Optional fields:

- `SourceType`: `str`

<a id="trialsummarytypedef"></a>

## TrialSummaryTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialSummaryTypeDef
```

Optional fields:

- `TrialArn`: `str`
- `TrialName`: `str`
- `DisplayName`: `str`
- `TrialSource`: [TrialSourceTypeDef](./type_defs.md#trialsourcetypedef)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="trialtypedef"></a>

## TrialTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TrialTypeDef
```

Optional fields:

- `TrialName`: `str`
- `TrialArn`: `str`
- `DisplayName`: `str`
- `ExperimentName`: `str`
- `Source`: [TrialSourceTypeDef](./type_defs.md#trialsourcetypedef)
- `CreationTime`: `datetime`
- `CreatedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `LastModifiedTime`: `datetime`
- `LastModifiedBy`: [UserContextTypeDef](./type_defs.md#usercontexttypedef)
- `MetadataProperties`:
  [MetadataPropertiesTypeDef](./type_defs.md#metadatapropertiestypedef)
- `Tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `TrialComponentSummaries`:
  `List`\[[TrialComponentSimpleSummaryTypeDef](./type_defs.md#trialcomponentsimplesummarytypedef)\]

<a id="tuningjobcompletioncriteriatypedef"></a>

## TuningJobCompletionCriteriaTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TuningJobCompletionCriteriaTypeDef
```

Required fields:

- `TargetObjectiveMetricValue`: `float`

<a id="tuningjobstepmetadatatypedef"></a>

## TuningJobStepMetaDataTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import TuningJobStepMetaDataTypeDef
```

Optional fields:

- `Arn`: `str`

<a id="usdtypedef"></a>

## USDTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import USDTypeDef
```

Optional fields:

- `Dollars`: `int`
- `Cents`: `int`
- `TenthFractionsOfACent`: `int`

<a id="uiconfigtypedef"></a>

## UiConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UiConfigTypeDef
```

Optional fields:

- `UiTemplateS3Uri`: `str`
- `HumanTaskUiArn`: `str`

<a id="uitemplateinfotypedef"></a>

## UiTemplateInfoTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UiTemplateInfoTypeDef
```

Optional fields:

- `Url`: `str`
- `ContentSha256`: `str`

<a id="uitemplatetypedef"></a>

## UiTemplateTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UiTemplateTypeDef
```

Required fields:

- `Content`: `str`

<a id="updateactionrequestrequesttypedef"></a>

## UpdateActionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateActionRequestRequestTypeDef
```

Required fields:

- `ActionName`: `str`

Optional fields:

- `Description`: `str`
- `Status`: [ActionStatusType](./literals.md#actionstatustype)
- `Properties`: `Mapping`\[`str`, `str`\]
- `PropertiesToRemove`: `Sequence`\[`str`\]

<a id="updateactionresponsetypedef"></a>

## UpdateActionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateActionResponseTypeDef
```

Required fields:

- `ActionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateappimageconfigrequestrequesttypedef"></a>

## UpdateAppImageConfigRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateAppImageConfigRequestRequestTypeDef
```

Required fields:

- `AppImageConfigName`: `str`

Optional fields:

- `KernelGatewayImageConfig`:
  [KernelGatewayImageConfigTypeDef](./type_defs.md#kernelgatewayimageconfigtypedef)

<a id="updateappimageconfigresponsetypedef"></a>

## UpdateAppImageConfigResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateAppImageConfigResponseTypeDef
```

Required fields:

- `AppImageConfigArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateartifactrequestrequesttypedef"></a>

## UpdateArtifactRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateArtifactRequestRequestTypeDef
```

Required fields:

- `ArtifactArn`: `str`

Optional fields:

- `ArtifactName`: `str`
- `Properties`: `Mapping`\[`str`, `str`\]
- `PropertiesToRemove`: `Sequence`\[`str`\]

<a id="updateartifactresponsetypedef"></a>

## UpdateArtifactResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateArtifactResponseTypeDef
```

Required fields:

- `ArtifactArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatecoderepositoryinputrequesttypedef"></a>

## UpdateCodeRepositoryInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateCodeRepositoryInputRequestTypeDef
```

Required fields:

- `CodeRepositoryName`: `str`

Optional fields:

- `GitConfig`:
  [GitConfigForUpdateTypeDef](./type_defs.md#gitconfigforupdatetypedef)

<a id="updatecoderepositoryoutputtypedef"></a>

## UpdateCodeRepositoryOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateCodeRepositoryOutputTypeDef
```

Required fields:

- `CodeRepositoryArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatecontextrequestrequesttypedef"></a>

## UpdateContextRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateContextRequestRequestTypeDef
```

Required fields:

- `ContextName`: `str`

Optional fields:

- `Description`: `str`
- `Properties`: `Mapping`\[`str`, `str`\]
- `PropertiesToRemove`: `Sequence`\[`str`\]

<a id="updatecontextresponsetypedef"></a>

## UpdateContextResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateContextResponseTypeDef
```

Required fields:

- `ContextArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatedevicefleetrequestrequesttypedef"></a>

## UpdateDeviceFleetRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateDeviceFleetRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `OutputConfig`:
  [EdgeOutputConfigTypeDef](./type_defs.md#edgeoutputconfigtypedef)

Optional fields:

- `RoleArn`: `str`
- `Description`: `str`
- `EnableIotRoleAlias`: `bool`

<a id="updatedevicesrequestrequesttypedef"></a>

## UpdateDevicesRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateDevicesRequestRequestTypeDef
```

Required fields:

- `DeviceFleetName`: `str`
- `Devices`: `Sequence`\[[DeviceTypeDef](./type_defs.md#devicetypedef)\]

<a id="updatedomainrequestrequesttypedef"></a>

## UpdateDomainRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateDomainRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`

Optional fields:

- `DefaultUserSettings`:
  [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)
- `DomainSettingsForUpdate`:
  [DomainSettingsForUpdateTypeDef](./type_defs.md#domainsettingsforupdatetypedef)

<a id="updatedomainresponsetypedef"></a>

## UpdateDomainResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateDomainResponseTypeDef
```

Required fields:

- `DomainArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateendpointinputrequesttypedef"></a>

## UpdateEndpointInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateEndpointInputRequestTypeDef
```

Required fields:

- `EndpointName`: `str`
- `EndpointConfigName`: `str`

Optional fields:

- `RetainAllVariantProperties`: `bool`
- `ExcludeRetainedVariantProperties`:
  `Sequence`\[[VariantPropertyTypeDef](./type_defs.md#variantpropertytypedef)\]
- `DeploymentConfig`:
  [DeploymentConfigTypeDef](./type_defs.md#deploymentconfigtypedef)
- `RetainDeploymentConfig`: `bool`

<a id="updateendpointoutputtypedef"></a>

## UpdateEndpointOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateEndpointOutputTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateendpointweightsandcapacitiesinputrequesttypedef"></a>

## UpdateEndpointWeightsAndCapacitiesInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateEndpointWeightsAndCapacitiesInputRequestTypeDef
```

Required fields:

- `EndpointName`: `str`
- `DesiredWeightsAndCapacities`:
  `Sequence`\[[DesiredWeightAndCapacityTypeDef](./type_defs.md#desiredweightandcapacitytypedef)\]

<a id="updateendpointweightsandcapacitiesoutputtypedef"></a>

## UpdateEndpointWeightsAndCapacitiesOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateEndpointWeightsAndCapacitiesOutputTypeDef
```

Required fields:

- `EndpointArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateexperimentrequestrequesttypedef"></a>

## UpdateExperimentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateExperimentRequestRequestTypeDef
```

Required fields:

- `ExperimentName`: `str`

Optional fields:

- `DisplayName`: `str`
- `Description`: `str`

<a id="updateexperimentresponsetypedef"></a>

## UpdateExperimentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateExperimentResponseTypeDef
```

Required fields:

- `ExperimentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateimagerequestrequesttypedef"></a>

## UpdateImageRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateImageRequestRequestTypeDef
```

Required fields:

- `ImageName`: `str`

Optional fields:

- `DeleteProperties`: `Sequence`\[`str`\]
- `Description`: `str`
- `DisplayName`: `str`
- `RoleArn`: `str`

<a id="updateimageresponsetypedef"></a>

## UpdateImageResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateImageResponseTypeDef
```

Required fields:

- `ImageArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatemodelpackageinputrequesttypedef"></a>

## UpdateModelPackageInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateModelPackageInputRequestTypeDef
```

Required fields:

- `ModelPackageArn`: `str`

Optional fields:

- `ModelApprovalStatus`:
  [ModelApprovalStatusType](./literals.md#modelapprovalstatustype)
- `ApprovalDescription`: `str`
- `CustomerMetadataProperties`: `Mapping`\[`str`, `str`\]
- `CustomerMetadataPropertiesToRemove`: `Sequence`\[`str`\]
- `AdditionalInferenceSpecificationsToAdd`:
  `Sequence`\[[AdditionalInferenceSpecificationDefinitionTypeDef](./type_defs.md#additionalinferencespecificationdefinitiontypedef)\]

<a id="updatemodelpackageoutputtypedef"></a>

## UpdateModelPackageOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateModelPackageOutputTypeDef
```

Required fields:

- `ModelPackageArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatemonitoringschedulerequestrequesttypedef"></a>

## UpdateMonitoringScheduleRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateMonitoringScheduleRequestRequestTypeDef
```

Required fields:

- `MonitoringScheduleName`: `str`
- `MonitoringScheduleConfig`:
  [MonitoringScheduleConfigTypeDef](./type_defs.md#monitoringscheduleconfigtypedef)

<a id="updatemonitoringscheduleresponsetypedef"></a>

## UpdateMonitoringScheduleResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateMonitoringScheduleResponseTypeDef
```

Required fields:

- `MonitoringScheduleArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatenotebookinstanceinputrequesttypedef"></a>

## UpdateNotebookInstanceInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateNotebookInstanceInputRequestTypeDef
```

Required fields:

- `NotebookInstanceName`: `str`

Optional fields:

- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `RoleArn`: `str`
- `LifecycleConfigName`: `str`
- `DisassociateLifecycleConfig`: `bool`
- `VolumeSizeInGB`: `int`
- `DefaultCodeRepository`: `str`
- `AdditionalCodeRepositories`: `Sequence`\[`str`\]
- `AcceleratorTypes`:
  `Sequence`\[[NotebookInstanceAcceleratorTypeType](./literals.md#notebookinstanceacceleratortypetype)\]
- `DisassociateAcceleratorTypes`: `bool`
- `DisassociateDefaultCodeRepository`: `bool`
- `DisassociateAdditionalCodeRepositories`: `bool`
- `RootAccess`: [RootAccessType](./literals.md#rootaccesstype)

<a id="updatenotebookinstancelifecycleconfiginputrequesttypedef"></a>

## UpdateNotebookInstanceLifecycleConfigInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateNotebookInstanceLifecycleConfigInputRequestTypeDef
```

Required fields:

- `NotebookInstanceLifecycleConfigName`: `str`

Optional fields:

- `OnCreate`:
  `Sequence`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]
- `OnStart`:
  `Sequence`\[[NotebookInstanceLifecycleHookTypeDef](./type_defs.md#notebookinstancelifecyclehooktypedef)\]

<a id="updatepipelineexecutionrequestrequesttypedef"></a>

## UpdatePipelineExecutionRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdatePipelineExecutionRequestRequestTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`

Optional fields:

- `PipelineExecutionDescription`: `str`
- `PipelineExecutionDisplayName`: `str`
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)

<a id="updatepipelineexecutionresponsetypedef"></a>

## UpdatePipelineExecutionResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdatePipelineExecutionResponseTypeDef
```

Required fields:

- `PipelineExecutionArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatepipelinerequestrequesttypedef"></a>

## UpdatePipelineRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdatePipelineRequestRequestTypeDef
```

Required fields:

- `PipelineName`: `str`

Optional fields:

- `PipelineDisplayName`: `str`
- `PipelineDefinition`: `str`
- `PipelineDefinitionS3Location`:
  [PipelineDefinitionS3LocationTypeDef](./type_defs.md#pipelinedefinitions3locationtypedef)
- `PipelineDescription`: `str`
- `RoleArn`: `str`
- `ParallelismConfiguration`:
  [ParallelismConfigurationTypeDef](./type_defs.md#parallelismconfigurationtypedef)

<a id="updatepipelineresponsetypedef"></a>

## UpdatePipelineResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdatePipelineResponseTypeDef
```

Required fields:

- `PipelineArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateprojectinputrequesttypedef"></a>

## UpdateProjectInputRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateProjectInputRequestTypeDef
```

Required fields:

- `ProjectName`: `str`

Optional fields:

- `ProjectDescription`: `str`
- `ServiceCatalogProvisioningUpdateDetails`:
  [ServiceCatalogProvisioningUpdateDetailsTypeDef](./type_defs.md#servicecatalogprovisioningupdatedetailstypedef)
- `Tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="updateprojectoutputtypedef"></a>

## UpdateProjectOutputTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateProjectOutputTypeDef
```

Required fields:

- `ProjectArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatetrainingjobrequestrequesttypedef"></a>

## UpdateTrainingJobRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrainingJobRequestRequestTypeDef
```

Required fields:

- `TrainingJobName`: `str`

Optional fields:

- `ProfilerConfig`:
  [ProfilerConfigForUpdateTypeDef](./type_defs.md#profilerconfigforupdatetypedef)
- `ProfilerRuleConfigurations`:
  `Sequence`\[[ProfilerRuleConfigurationTypeDef](./type_defs.md#profilerruleconfigurationtypedef)\]

<a id="updatetrainingjobresponsetypedef"></a>

## UpdateTrainingJobResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrainingJobResponseTypeDef
```

Required fields:

- `TrainingJobArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatetrialcomponentrequestrequesttypedef"></a>

## UpdateTrialComponentRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrialComponentRequestRequestTypeDef
```

Required fields:

- `TrialComponentName`: `str`

Optional fields:

- `DisplayName`: `str`
- `Status`:
  [TrialComponentStatusTypeDef](./type_defs.md#trialcomponentstatustypedef)
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `Parameters`: `Mapping`\[`str`,
  [TrialComponentParameterValueTypeDef](./type_defs.md#trialcomponentparametervaluetypedef)\]
- `ParametersToRemove`: `Sequence`\[`str`\]
- `InputArtifacts`: `Mapping`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `InputArtifactsToRemove`: `Sequence`\[`str`\]
- `OutputArtifacts`: `Mapping`\[`str`,
  [TrialComponentArtifactTypeDef](./type_defs.md#trialcomponentartifacttypedef)\]
- `OutputArtifactsToRemove`: `Sequence`\[`str`\]

<a id="updatetrialcomponentresponsetypedef"></a>

## UpdateTrialComponentResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrialComponentResponseTypeDef
```

Required fields:

- `TrialComponentArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updatetrialrequestrequesttypedef"></a>

## UpdateTrialRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrialRequestRequestTypeDef
```

Required fields:

- `TrialName`: `str`

Optional fields:

- `DisplayName`: `str`

<a id="updatetrialresponsetypedef"></a>

## UpdateTrialResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateTrialResponseTypeDef
```

Required fields:

- `TrialArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateuserprofilerequestrequesttypedef"></a>

## UpdateUserProfileRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateUserProfileRequestRequestTypeDef
```

Required fields:

- `DomainId`: `str`
- `UserProfileName`: `str`

Optional fields:

- `UserSettings`: [UserSettingsTypeDef](./type_defs.md#usersettingstypedef)

<a id="updateuserprofileresponsetypedef"></a>

## UpdateUserProfileResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateUserProfileResponseTypeDef
```

Required fields:

- `UserProfileArn`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateworkforcerequestrequesttypedef"></a>

## UpdateWorkforceRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateWorkforceRequestRequestTypeDef
```

Required fields:

- `WorkforceName`: `str`

Optional fields:

- `SourceIpConfig`:
  [SourceIpConfigTypeDef](./type_defs.md#sourceipconfigtypedef)
- `OidcConfig`: [OidcConfigTypeDef](./type_defs.md#oidcconfigtypedef)

<a id="updateworkforceresponsetypedef"></a>

## UpdateWorkforceResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateWorkforceResponseTypeDef
```

Required fields:

- `Workforce`: [WorkforceTypeDef](./type_defs.md#workforcetypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="updateworkteamrequestrequesttypedef"></a>

## UpdateWorkteamRequestRequestTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateWorkteamRequestRequestTypeDef
```

Required fields:

- `WorkteamName`: `str`

Optional fields:

- `MemberDefinitions`:
  `Sequence`\[[MemberDefinitionTypeDef](./type_defs.md#memberdefinitiontypedef)\]
- `Description`: `str`
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)

<a id="updateworkteamresponsetypedef"></a>

## UpdateWorkteamResponseTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UpdateWorkteamResponseTypeDef
```

Required fields:

- `Workteam`: [WorkteamTypeDef](./type_defs.md#workteamtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="usercontexttypedef"></a>

## UserContextTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UserContextTypeDef
```

Optional fields:

- `UserProfileArn`: `str`
- `UserProfileName`: `str`
- `DomainId`: `str`

<a id="userprofiledetailstypedef"></a>

## UserProfileDetailsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UserProfileDetailsTypeDef
```

Optional fields:

- `DomainId`: `str`
- `UserProfileName`: `str`
- `Status`: [UserProfileStatusType](./literals.md#userprofilestatustype)
- `CreationTime`: `datetime`
- `LastModifiedTime`: `datetime`

<a id="usersettingstypedef"></a>

## UserSettingsTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import UserSettingsTypeDef
```

Optional fields:

- `ExecutionRole`: `str`
- `SecurityGroups`: `Sequence`\[`str`\]
- `SharingSettings`:
  [SharingSettingsTypeDef](./type_defs.md#sharingsettingstypedef)
- `JupyterServerAppSettings`:
  [JupyterServerAppSettingsTypeDef](./type_defs.md#jupyterserverappsettingstypedef)
- `KernelGatewayAppSettings`:
  [KernelGatewayAppSettingsTypeDef](./type_defs.md#kernelgatewayappsettingstypedef)
- `TensorBoardAppSettings`:
  [TensorBoardAppSettingsTypeDef](./type_defs.md#tensorboardappsettingstypedef)
- `RStudioServerProAppSettings`:
  [RStudioServerProAppSettingsTypeDef](./type_defs.md#rstudioserverproappsettingstypedef)
- `RSessionAppSettings`: `Mapping`\[`str`, `Any`\]

<a id="variantpropertytypedef"></a>

## VariantPropertyTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import VariantPropertyTypeDef
```

Required fields:

- `VariantPropertyType`:
  [VariantPropertyTypeType](./literals.md#variantpropertytypetype)

<a id="vertextypedef"></a>

## VertexTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import VertexTypeDef
```

Optional fields:

- `Arn`: `str`
- `Type`: `str`
- `LineageType`: [LineageTypeType](./literals.md#lineagetypetype)

<a id="vpcconfigtypedef"></a>

## VpcConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import VpcConfigTypeDef
```

Required fields:

- `SecurityGroupIds`: `Sequence`\[`str`\]
- `Subnets`: `Sequence`\[`str`\]

<a id="waiterconfigtypedef"></a>

## WaiterConfigTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import WaiterConfigTypeDef
```

Optional fields:

- `Delay`: `int`
- `MaxAttempts`: `int`

<a id="workforcetypedef"></a>

## WorkforceTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import WorkforceTypeDef
```

Required fields:

- `WorkforceName`: `str`
- `WorkforceArn`: `str`

Optional fields:

- `LastUpdatedDate`: `datetime`
- `SourceIpConfig`:
  [SourceIpConfigTypeDef](./type_defs.md#sourceipconfigtypedef)
- `SubDomain`: `str`
- `CognitoConfig`: [CognitoConfigTypeDef](./type_defs.md#cognitoconfigtypedef)
- `OidcConfig`:
  [OidcConfigForResponseTypeDef](./type_defs.md#oidcconfigforresponsetypedef)
- `CreateDate`: `datetime`

<a id="workteamtypedef"></a>

## WorkteamTypeDef

```python
from types_aiobotocore_sagemaker.type_defs import WorkteamTypeDef
```

Required fields:

- `WorkteamName`: `str`
- `MemberDefinitions`:
  `List`\[[MemberDefinitionTypeDef](./type_defs.md#memberdefinitiontypedef)\]
- `WorkteamArn`: `str`
- `Description`: `str`

Optional fields:

- `WorkforceArn`: `str`
- `ProductListingIds`: `List`\[`str`\]
- `SubDomain`: `str`
- `CreateDate`: `datetime`
- `LastUpdatedDate`: `datetime`
- `NotificationConfiguration`:
  [NotificationConfigurationTypeDef](./type_defs.md#notificationconfigurationtypedef)
