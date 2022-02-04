<a id="type-annotations-for-aiobotocore-clouddirectory-module"></a>

# Type annotations for aiobotocore CloudDirectory module

> [Index](..) > CloudDirectory

Auto-generated documentation for
[CloudDirectory](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
type annotations stubs module
[types-aiobotocore-clouddirectory](https://pypi.org/project/types-aiobotocore-clouddirectory/).

```bash
# install with types-aiobotocore
pip install 'types-aiobotocore[clouddirectory]'

# install as a standalone
pip install types-aiobotocore-clouddirectory
```

- [Type annotations for aiobotocore CloudDirectory module](#type-annotations-for-aiobotocore-clouddirectory-module)
  - [CloudDirectoryClient](#clouddirectoryclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Paginators](#paginators)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="clouddirectoryclient"></a>

## CloudDirectoryClient

Type annotations for `aiobotocore.create_client("clouddirectory")` as
[CloudDirectoryClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_clouddirectory.client import CloudDirectoryClient
```

<a id="methods"></a>

### Methods

- [add_facet_to_object](./client.md#add_facet_to_object)
- [apply_schema](./client.md#apply_schema)
- [attach_object](./client.md#attach_object)
- [attach_policy](./client.md#attach_policy)
- [attach_to_index](./client.md#attach_to_index)
- [attach_typed_link](./client.md#attach_typed_link)
- [batch_read](./client.md#batch_read)
- [batch_write](./client.md#batch_write)
- [can_paginate](./client.md#can_paginate)
- [create_directory](./client.md#create_directory)
- [create_facet](./client.md#create_facet)
- [create_index](./client.md#create_index)
- [create_object](./client.md#create_object)
- [create_schema](./client.md#create_schema)
- [create_typed_link_facet](./client.md#create_typed_link_facet)
- [delete_directory](./client.md#delete_directory)
- [delete_facet](./client.md#delete_facet)
- [delete_object](./client.md#delete_object)
- [delete_schema](./client.md#delete_schema)
- [delete_typed_link_facet](./client.md#delete_typed_link_facet)
- [detach_from_index](./client.md#detach_from_index)
- [detach_object](./client.md#detach_object)
- [detach_policy](./client.md#detach_policy)
- [detach_typed_link](./client.md#detach_typed_link)
- [disable_directory](./client.md#disable_directory)
- [enable_directory](./client.md#enable_directory)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_applied_schema_version](./client.md#get_applied_schema_version)
- [get_directory](./client.md#get_directory)
- [get_facet](./client.md#get_facet)
- [get_link_attributes](./client.md#get_link_attributes)
- [get_object_attributes](./client.md#get_object_attributes)
- [get_object_information](./client.md#get_object_information)
- [get_paginator](./client.md#get_paginator)
- [get_schema_as_json](./client.md#get_schema_as_json)
- [get_typed_link_facet_information](./client.md#get_typed_link_facet_information)
- [list_applied_schema_arns](./client.md#list_applied_schema_arns)
- [list_attached_indices](./client.md#list_attached_indices)
- [list_development_schema_arns](./client.md#list_development_schema_arns)
- [list_directories](./client.md#list_directories)
- [list_facet_attributes](./client.md#list_facet_attributes)
- [list_facet_names](./client.md#list_facet_names)
- [list_incoming_typed_links](./client.md#list_incoming_typed_links)
- [list_index](./client.md#list_index)
- [list_managed_schema_arns](./client.md#list_managed_schema_arns)
- [list_object_attributes](./client.md#list_object_attributes)
- [list_object_children](./client.md#list_object_children)
- [list_object_parent_paths](./client.md#list_object_parent_paths)
- [list_object_parents](./client.md#list_object_parents)
- [list_object_policies](./client.md#list_object_policies)
- [list_outgoing_typed_links](./client.md#list_outgoing_typed_links)
- [list_policy_attachments](./client.md#list_policy_attachments)
- [list_published_schema_arns](./client.md#list_published_schema_arns)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [list_typed_link_facet_attributes](./client.md#list_typed_link_facet_attributes)
- [list_typed_link_facet_names](./client.md#list_typed_link_facet_names)
- [lookup_policy](./client.md#lookup_policy)
- [publish_schema](./client.md#publish_schema)
- [put_schema_from_json](./client.md#put_schema_from_json)
- [remove_facet_from_object](./client.md#remove_facet_from_object)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_facet](./client.md#update_facet)
- [update_link_attributes](./client.md#update_link_attributes)
- [update_object_attributes](./client.md#update_object_attributes)
- [update_schema](./client.md#update_schema)
- [update_typed_link_facet](./client.md#update_typed_link_facet)
- [upgrade_applied_schema](./client.md#upgrade_applied_schema)
- [upgrade_published_schema](./client.md#upgrade_published_schema)

<a id="exceptions"></a>

### Exceptions

CloudDirectoryClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- BatchWriteException
- CannotListParentOfRootException
- ClientError
- DirectoryAlreadyExistsException
- DirectoryDeletedException
- DirectoryNotDisabledException
- DirectoryNotEnabledException
- FacetAlreadyExistsException
- FacetInUseException
- FacetNotFoundException
- FacetValidationException
- IncompatibleSchemaException
- IndexedAttributeMissingException
- InternalServiceException
- InvalidArnException
- InvalidAttachmentException
- InvalidFacetUpdateException
- InvalidNextTokenException
- InvalidRuleException
- InvalidSchemaDocException
- InvalidTaggingRequestException
- LimitExceededException
- LinkNameAlreadyInUseException
- NotIndexException
- NotNodeException
- NotPolicyException
- ObjectAlreadyDetachedException
- ObjectNotDetachedException
- ResourceNotFoundException
- RetryableConflictException
- SchemaAlreadyExistsException
- SchemaAlreadyPublishedException
- StillContainsLinksException
- UnsupportedIndexTypeException
- ValidationException

<a id="paginators"></a>

## Paginators

Type annotations for [paginators](./paginators.md) from
`boto3.client("clouddirectory").get_paginator("...")`.

Can be used directly:

```python
from types_aiobotocore_clouddirectory.paginators import ListAppliedSchemaArnsPaginator, ...
```

- [ListAppliedSchemaArnsPaginator](./paginators.md#listappliedschemaarnspaginator)
- [ListAttachedIndicesPaginator](./paginators.md#listattachedindicespaginator)
- [ListDevelopmentSchemaArnsPaginator](./paginators.md#listdevelopmentschemaarnspaginator)
- [ListDirectoriesPaginator](./paginators.md#listdirectoriespaginator)
- [ListFacetAttributesPaginator](./paginators.md#listfacetattributespaginator)
- [ListFacetNamesPaginator](./paginators.md#listfacetnamespaginator)
- [ListIncomingTypedLinksPaginator](./paginators.md#listincomingtypedlinkspaginator)
- [ListIndexPaginator](./paginators.md#listindexpaginator)
- [ListManagedSchemaArnsPaginator](./paginators.md#listmanagedschemaarnspaginator)
- [ListObjectAttributesPaginator](./paginators.md#listobjectattributespaginator)
- [ListObjectParentPathsPaginator](./paginators.md#listobjectparentpathspaginator)
- [ListObjectPoliciesPaginator](./paginators.md#listobjectpoliciespaginator)
- [ListOutgoingTypedLinksPaginator](./paginators.md#listoutgoingtypedlinkspaginator)
- [ListPolicyAttachmentsPaginator](./paginators.md#listpolicyattachmentspaginator)
- [ListPublishedSchemaArnsPaginator](./paginators.md#listpublishedschemaarnspaginator)
- [ListTagsForResourcePaginator](./paginators.md#listtagsforresourcepaginator)
- [ListTypedLinkFacetAttributesPaginator](./paginators.md#listtypedlinkfacetattributespaginator)
- [ListTypedLinkFacetNamesPaginator](./paginators.md#listtypedlinkfacetnamespaginator)
- [LookupPolicyPaginator](./paginators.md#lookuppolicypaginator)

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_clouddirectory.literals import BatchReadExceptionTypeType, ...
```

- [BatchReadExceptionTypeType](./literals.md#batchreadexceptiontypetype)
- [ConsistencyLevelType](./literals.md#consistencyleveltype)
- [DirectoryStateType](./literals.md#directorystatetype)
- [FacetAttributeTypeType](./literals.md#facetattributetypetype)
- [FacetStyleType](./literals.md#facetstyletype)
- [ListAppliedSchemaArnsPaginatorName](./literals.md#listappliedschemaarnspaginatorname)
- [ListAttachedIndicesPaginatorName](./literals.md#listattachedindicespaginatorname)
- [ListDevelopmentSchemaArnsPaginatorName](./literals.md#listdevelopmentschemaarnspaginatorname)
- [ListDirectoriesPaginatorName](./literals.md#listdirectoriespaginatorname)
- [ListFacetAttributesPaginatorName](./literals.md#listfacetattributespaginatorname)
- [ListFacetNamesPaginatorName](./literals.md#listfacetnamespaginatorname)
- [ListIncomingTypedLinksPaginatorName](./literals.md#listincomingtypedlinkspaginatorname)
- [ListIndexPaginatorName](./literals.md#listindexpaginatorname)
- [ListManagedSchemaArnsPaginatorName](./literals.md#listmanagedschemaarnspaginatorname)
- [ListObjectAttributesPaginatorName](./literals.md#listobjectattributespaginatorname)
- [ListObjectParentPathsPaginatorName](./literals.md#listobjectparentpathspaginatorname)
- [ListObjectPoliciesPaginatorName](./literals.md#listobjectpoliciespaginatorname)
- [ListOutgoingTypedLinksPaginatorName](./literals.md#listoutgoingtypedlinkspaginatorname)
- [ListPolicyAttachmentsPaginatorName](./literals.md#listpolicyattachmentspaginatorname)
- [ListPublishedSchemaArnsPaginatorName](./literals.md#listpublishedschemaarnspaginatorname)
- [ListTagsForResourcePaginatorName](./literals.md#listtagsforresourcepaginatorname)
- [ListTypedLinkFacetAttributesPaginatorName](./literals.md#listtypedlinkfacetattributespaginatorname)
- [ListTypedLinkFacetNamesPaginatorName](./literals.md#listtypedlinkfacetnamespaginatorname)
- [LookupPolicyPaginatorName](./literals.md#lookuppolicypaginatorname)
- [ObjectTypeType](./literals.md#objecttypetype)
- [RangeModeType](./literals.md#rangemodetype)
- [RequiredAttributeBehaviorType](./literals.md#requiredattributebehaviortype)
- [RuleTypeType](./literals.md#ruletypetype)
- [UpdateActionTypeType](./literals.md#updateactiontypetype)
- [ServiceName](./literals.md#servicename)
- [PaginatorName](./literals.md#paginatorname)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_clouddirectory.type_defs import AddFacetToObjectRequestRequestTypeDef, ...
```

- [AddFacetToObjectRequestRequestTypeDef](./type_defs.md#addfacettoobjectrequestrequesttypedef)
- [ApplySchemaRequestRequestTypeDef](./type_defs.md#applyschemarequestrequesttypedef)
- [ApplySchemaResponseTypeDef](./type_defs.md#applyschemaresponsetypedef)
- [AttachObjectRequestRequestTypeDef](./type_defs.md#attachobjectrequestrequesttypedef)
- [AttachObjectResponseTypeDef](./type_defs.md#attachobjectresponsetypedef)
- [AttachPolicyRequestRequestTypeDef](./type_defs.md#attachpolicyrequestrequesttypedef)
- [AttachToIndexRequestRequestTypeDef](./type_defs.md#attachtoindexrequestrequesttypedef)
- [AttachToIndexResponseTypeDef](./type_defs.md#attachtoindexresponsetypedef)
- [AttachTypedLinkRequestRequestTypeDef](./type_defs.md#attachtypedlinkrequestrequesttypedef)
- [AttachTypedLinkResponseTypeDef](./type_defs.md#attachtypedlinkresponsetypedef)
- [AttributeKeyAndValueTypeDef](./type_defs.md#attributekeyandvaluetypedef)
- [AttributeKeyTypeDef](./type_defs.md#attributekeytypedef)
- [AttributeNameAndValueTypeDef](./type_defs.md#attributenameandvaluetypedef)
- [BatchAddFacetToObjectTypeDef](./type_defs.md#batchaddfacettoobjecttypedef)
- [BatchAttachObjectResponseTypeDef](./type_defs.md#batchattachobjectresponsetypedef)
- [BatchAttachObjectTypeDef](./type_defs.md#batchattachobjecttypedef)
- [BatchAttachPolicyTypeDef](./type_defs.md#batchattachpolicytypedef)
- [BatchAttachToIndexResponseTypeDef](./type_defs.md#batchattachtoindexresponsetypedef)
- [BatchAttachToIndexTypeDef](./type_defs.md#batchattachtoindextypedef)
- [BatchAttachTypedLinkResponseTypeDef](./type_defs.md#batchattachtypedlinkresponsetypedef)
- [BatchAttachTypedLinkTypeDef](./type_defs.md#batchattachtypedlinktypedef)
- [BatchCreateIndexResponseTypeDef](./type_defs.md#batchcreateindexresponsetypedef)
- [BatchCreateIndexTypeDef](./type_defs.md#batchcreateindextypedef)
- [BatchCreateObjectResponseTypeDef](./type_defs.md#batchcreateobjectresponsetypedef)
- [BatchCreateObjectTypeDef](./type_defs.md#batchcreateobjecttypedef)
- [BatchDeleteObjectTypeDef](./type_defs.md#batchdeleteobjecttypedef)
- [BatchDetachFromIndexResponseTypeDef](./type_defs.md#batchdetachfromindexresponsetypedef)
- [BatchDetachFromIndexTypeDef](./type_defs.md#batchdetachfromindextypedef)
- [BatchDetachObjectResponseTypeDef](./type_defs.md#batchdetachobjectresponsetypedef)
- [BatchDetachObjectTypeDef](./type_defs.md#batchdetachobjecttypedef)
- [BatchDetachPolicyTypeDef](./type_defs.md#batchdetachpolicytypedef)
- [BatchDetachTypedLinkTypeDef](./type_defs.md#batchdetachtypedlinktypedef)
- [BatchGetLinkAttributesResponseTypeDef](./type_defs.md#batchgetlinkattributesresponsetypedef)
- [BatchGetLinkAttributesTypeDef](./type_defs.md#batchgetlinkattributestypedef)
- [BatchGetObjectAttributesResponseTypeDef](./type_defs.md#batchgetobjectattributesresponsetypedef)
- [BatchGetObjectAttributesTypeDef](./type_defs.md#batchgetobjectattributestypedef)
- [BatchGetObjectInformationResponseTypeDef](./type_defs.md#batchgetobjectinformationresponsetypedef)
- [BatchGetObjectInformationTypeDef](./type_defs.md#batchgetobjectinformationtypedef)
- [BatchListAttachedIndicesResponseTypeDef](./type_defs.md#batchlistattachedindicesresponsetypedef)
- [BatchListAttachedIndicesTypeDef](./type_defs.md#batchlistattachedindicestypedef)
- [BatchListIncomingTypedLinksResponseTypeDef](./type_defs.md#batchlistincomingtypedlinksresponsetypedef)
- [BatchListIncomingTypedLinksTypeDef](./type_defs.md#batchlistincomingtypedlinkstypedef)
- [BatchListIndexResponseTypeDef](./type_defs.md#batchlistindexresponsetypedef)
- [BatchListIndexTypeDef](./type_defs.md#batchlistindextypedef)
- [BatchListObjectAttributesResponseTypeDef](./type_defs.md#batchlistobjectattributesresponsetypedef)
- [BatchListObjectAttributesTypeDef](./type_defs.md#batchlistobjectattributestypedef)
- [BatchListObjectChildrenResponseTypeDef](./type_defs.md#batchlistobjectchildrenresponsetypedef)
- [BatchListObjectChildrenTypeDef](./type_defs.md#batchlistobjectchildrentypedef)
- [BatchListObjectParentPathsResponseTypeDef](./type_defs.md#batchlistobjectparentpathsresponsetypedef)
- [BatchListObjectParentPathsTypeDef](./type_defs.md#batchlistobjectparentpathstypedef)
- [BatchListObjectParentsResponseTypeDef](./type_defs.md#batchlistobjectparentsresponsetypedef)
- [BatchListObjectParentsTypeDef](./type_defs.md#batchlistobjectparentstypedef)
- [BatchListObjectPoliciesResponseTypeDef](./type_defs.md#batchlistobjectpoliciesresponsetypedef)
- [BatchListObjectPoliciesTypeDef](./type_defs.md#batchlistobjectpoliciestypedef)
- [BatchListOutgoingTypedLinksResponseTypeDef](./type_defs.md#batchlistoutgoingtypedlinksresponsetypedef)
- [BatchListOutgoingTypedLinksTypeDef](./type_defs.md#batchlistoutgoingtypedlinkstypedef)
- [BatchListPolicyAttachmentsResponseTypeDef](./type_defs.md#batchlistpolicyattachmentsresponsetypedef)
- [BatchListPolicyAttachmentsTypeDef](./type_defs.md#batchlistpolicyattachmentstypedef)
- [BatchLookupPolicyResponseTypeDef](./type_defs.md#batchlookuppolicyresponsetypedef)
- [BatchLookupPolicyTypeDef](./type_defs.md#batchlookuppolicytypedef)
- [BatchReadExceptionTypeDef](./type_defs.md#batchreadexceptiontypedef)
- [BatchReadOperationResponseTypeDef](./type_defs.md#batchreadoperationresponsetypedef)
- [BatchReadOperationTypeDef](./type_defs.md#batchreadoperationtypedef)
- [BatchReadRequestRequestTypeDef](./type_defs.md#batchreadrequestrequesttypedef)
- [BatchReadResponseTypeDef](./type_defs.md#batchreadresponsetypedef)
- [BatchReadSuccessfulResponseTypeDef](./type_defs.md#batchreadsuccessfulresponsetypedef)
- [BatchRemoveFacetFromObjectTypeDef](./type_defs.md#batchremovefacetfromobjecttypedef)
- [BatchUpdateLinkAttributesTypeDef](./type_defs.md#batchupdatelinkattributestypedef)
- [BatchUpdateObjectAttributesResponseTypeDef](./type_defs.md#batchupdateobjectattributesresponsetypedef)
- [BatchUpdateObjectAttributesTypeDef](./type_defs.md#batchupdateobjectattributestypedef)
- [BatchWriteOperationResponseTypeDef](./type_defs.md#batchwriteoperationresponsetypedef)
- [BatchWriteOperationTypeDef](./type_defs.md#batchwriteoperationtypedef)
- [BatchWriteRequestRequestTypeDef](./type_defs.md#batchwriterequestrequesttypedef)
- [BatchWriteResponseTypeDef](./type_defs.md#batchwriteresponsetypedef)
- [CreateDirectoryRequestRequestTypeDef](./type_defs.md#createdirectoryrequestrequesttypedef)
- [CreateDirectoryResponseTypeDef](./type_defs.md#createdirectoryresponsetypedef)
- [CreateFacetRequestRequestTypeDef](./type_defs.md#createfacetrequestrequesttypedef)
- [CreateIndexRequestRequestTypeDef](./type_defs.md#createindexrequestrequesttypedef)
- [CreateIndexResponseTypeDef](./type_defs.md#createindexresponsetypedef)
- [CreateObjectRequestRequestTypeDef](./type_defs.md#createobjectrequestrequesttypedef)
- [CreateObjectResponseTypeDef](./type_defs.md#createobjectresponsetypedef)
- [CreateSchemaRequestRequestTypeDef](./type_defs.md#createschemarequestrequesttypedef)
- [CreateSchemaResponseTypeDef](./type_defs.md#createschemaresponsetypedef)
- [CreateTypedLinkFacetRequestRequestTypeDef](./type_defs.md#createtypedlinkfacetrequestrequesttypedef)
- [DeleteDirectoryRequestRequestTypeDef](./type_defs.md#deletedirectoryrequestrequesttypedef)
- [DeleteDirectoryResponseTypeDef](./type_defs.md#deletedirectoryresponsetypedef)
- [DeleteFacetRequestRequestTypeDef](./type_defs.md#deletefacetrequestrequesttypedef)
- [DeleteObjectRequestRequestTypeDef](./type_defs.md#deleteobjectrequestrequesttypedef)
- [DeleteSchemaRequestRequestTypeDef](./type_defs.md#deleteschemarequestrequesttypedef)
- [DeleteSchemaResponseTypeDef](./type_defs.md#deleteschemaresponsetypedef)
- [DeleteTypedLinkFacetRequestRequestTypeDef](./type_defs.md#deletetypedlinkfacetrequestrequesttypedef)
- [DetachFromIndexRequestRequestTypeDef](./type_defs.md#detachfromindexrequestrequesttypedef)
- [DetachFromIndexResponseTypeDef](./type_defs.md#detachfromindexresponsetypedef)
- [DetachObjectRequestRequestTypeDef](./type_defs.md#detachobjectrequestrequesttypedef)
- [DetachObjectResponseTypeDef](./type_defs.md#detachobjectresponsetypedef)
- [DetachPolicyRequestRequestTypeDef](./type_defs.md#detachpolicyrequestrequesttypedef)
- [DetachTypedLinkRequestRequestTypeDef](./type_defs.md#detachtypedlinkrequestrequesttypedef)
- [DirectoryTypeDef](./type_defs.md#directorytypedef)
- [DisableDirectoryRequestRequestTypeDef](./type_defs.md#disabledirectoryrequestrequesttypedef)
- [DisableDirectoryResponseTypeDef](./type_defs.md#disabledirectoryresponsetypedef)
- [EnableDirectoryRequestRequestTypeDef](./type_defs.md#enabledirectoryrequestrequesttypedef)
- [EnableDirectoryResponseTypeDef](./type_defs.md#enabledirectoryresponsetypedef)
- [FacetAttributeDefinitionTypeDef](./type_defs.md#facetattributedefinitiontypedef)
- [FacetAttributeReferenceTypeDef](./type_defs.md#facetattributereferencetypedef)
- [FacetAttributeTypeDef](./type_defs.md#facetattributetypedef)
- [FacetAttributeUpdateTypeDef](./type_defs.md#facetattributeupdatetypedef)
- [FacetTypeDef](./type_defs.md#facettypedef)
- [GetAppliedSchemaVersionRequestRequestTypeDef](./type_defs.md#getappliedschemaversionrequestrequesttypedef)
- [GetAppliedSchemaVersionResponseTypeDef](./type_defs.md#getappliedschemaversionresponsetypedef)
- [GetDirectoryRequestRequestTypeDef](./type_defs.md#getdirectoryrequestrequesttypedef)
- [GetDirectoryResponseTypeDef](./type_defs.md#getdirectoryresponsetypedef)
- [GetFacetRequestRequestTypeDef](./type_defs.md#getfacetrequestrequesttypedef)
- [GetFacetResponseTypeDef](./type_defs.md#getfacetresponsetypedef)
- [GetLinkAttributesRequestRequestTypeDef](./type_defs.md#getlinkattributesrequestrequesttypedef)
- [GetLinkAttributesResponseTypeDef](./type_defs.md#getlinkattributesresponsetypedef)
- [GetObjectAttributesRequestRequestTypeDef](./type_defs.md#getobjectattributesrequestrequesttypedef)
- [GetObjectAttributesResponseTypeDef](./type_defs.md#getobjectattributesresponsetypedef)
- [GetObjectInformationRequestRequestTypeDef](./type_defs.md#getobjectinformationrequestrequesttypedef)
- [GetObjectInformationResponseTypeDef](./type_defs.md#getobjectinformationresponsetypedef)
- [GetSchemaAsJsonRequestRequestTypeDef](./type_defs.md#getschemaasjsonrequestrequesttypedef)
- [GetSchemaAsJsonResponseTypeDef](./type_defs.md#getschemaasjsonresponsetypedef)
- [GetTypedLinkFacetInformationRequestRequestTypeDef](./type_defs.md#gettypedlinkfacetinformationrequestrequesttypedef)
- [GetTypedLinkFacetInformationResponseTypeDef](./type_defs.md#gettypedlinkfacetinformationresponsetypedef)
- [IndexAttachmentTypeDef](./type_defs.md#indexattachmenttypedef)
- [LinkAttributeActionTypeDef](./type_defs.md#linkattributeactiontypedef)
- [LinkAttributeUpdateTypeDef](./type_defs.md#linkattributeupdatetypedef)
- [ListAppliedSchemaArnsRequestRequestTypeDef](./type_defs.md#listappliedschemaarnsrequestrequesttypedef)
- [ListAppliedSchemaArnsResponseTypeDef](./type_defs.md#listappliedschemaarnsresponsetypedef)
- [ListAttachedIndicesRequestRequestTypeDef](./type_defs.md#listattachedindicesrequestrequesttypedef)
- [ListAttachedIndicesResponseTypeDef](./type_defs.md#listattachedindicesresponsetypedef)
- [ListDevelopmentSchemaArnsRequestRequestTypeDef](./type_defs.md#listdevelopmentschemaarnsrequestrequesttypedef)
- [ListDevelopmentSchemaArnsResponseTypeDef](./type_defs.md#listdevelopmentschemaarnsresponsetypedef)
- [ListDirectoriesRequestRequestTypeDef](./type_defs.md#listdirectoriesrequestrequesttypedef)
- [ListDirectoriesResponseTypeDef](./type_defs.md#listdirectoriesresponsetypedef)
- [ListFacetAttributesRequestRequestTypeDef](./type_defs.md#listfacetattributesrequestrequesttypedef)
- [ListFacetAttributesResponseTypeDef](./type_defs.md#listfacetattributesresponsetypedef)
- [ListFacetNamesRequestRequestTypeDef](./type_defs.md#listfacetnamesrequestrequesttypedef)
- [ListFacetNamesResponseTypeDef](./type_defs.md#listfacetnamesresponsetypedef)
- [ListIncomingTypedLinksRequestRequestTypeDef](./type_defs.md#listincomingtypedlinksrequestrequesttypedef)
- [ListIncomingTypedLinksResponseTypeDef](./type_defs.md#listincomingtypedlinksresponsetypedef)
- [ListIndexRequestRequestTypeDef](./type_defs.md#listindexrequestrequesttypedef)
- [ListIndexResponseTypeDef](./type_defs.md#listindexresponsetypedef)
- [ListManagedSchemaArnsRequestRequestTypeDef](./type_defs.md#listmanagedschemaarnsrequestrequesttypedef)
- [ListManagedSchemaArnsResponseTypeDef](./type_defs.md#listmanagedschemaarnsresponsetypedef)
- [ListObjectAttributesRequestRequestTypeDef](./type_defs.md#listobjectattributesrequestrequesttypedef)
- [ListObjectAttributesResponseTypeDef](./type_defs.md#listobjectattributesresponsetypedef)
- [ListObjectChildrenRequestRequestTypeDef](./type_defs.md#listobjectchildrenrequestrequesttypedef)
- [ListObjectChildrenResponseTypeDef](./type_defs.md#listobjectchildrenresponsetypedef)
- [ListObjectParentPathsRequestRequestTypeDef](./type_defs.md#listobjectparentpathsrequestrequesttypedef)
- [ListObjectParentPathsResponseTypeDef](./type_defs.md#listobjectparentpathsresponsetypedef)
- [ListObjectParentsRequestRequestTypeDef](./type_defs.md#listobjectparentsrequestrequesttypedef)
- [ListObjectParentsResponseTypeDef](./type_defs.md#listobjectparentsresponsetypedef)
- [ListObjectPoliciesRequestRequestTypeDef](./type_defs.md#listobjectpoliciesrequestrequesttypedef)
- [ListObjectPoliciesResponseTypeDef](./type_defs.md#listobjectpoliciesresponsetypedef)
- [ListOutgoingTypedLinksRequestRequestTypeDef](./type_defs.md#listoutgoingtypedlinksrequestrequesttypedef)
- [ListOutgoingTypedLinksResponseTypeDef](./type_defs.md#listoutgoingtypedlinksresponsetypedef)
- [ListPolicyAttachmentsRequestRequestTypeDef](./type_defs.md#listpolicyattachmentsrequestrequesttypedef)
- [ListPolicyAttachmentsResponseTypeDef](./type_defs.md#listpolicyattachmentsresponsetypedef)
- [ListPublishedSchemaArnsRequestRequestTypeDef](./type_defs.md#listpublishedschemaarnsrequestrequesttypedef)
- [ListPublishedSchemaArnsResponseTypeDef](./type_defs.md#listpublishedschemaarnsresponsetypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [ListTypedLinkFacetAttributesRequestRequestTypeDef](./type_defs.md#listtypedlinkfacetattributesrequestrequesttypedef)
- [ListTypedLinkFacetAttributesResponseTypeDef](./type_defs.md#listtypedlinkfacetattributesresponsetypedef)
- [ListTypedLinkFacetNamesRequestRequestTypeDef](./type_defs.md#listtypedlinkfacetnamesrequestrequesttypedef)
- [ListTypedLinkFacetNamesResponseTypeDef](./type_defs.md#listtypedlinkfacetnamesresponsetypedef)
- [LookupPolicyRequestRequestTypeDef](./type_defs.md#lookuppolicyrequestrequesttypedef)
- [LookupPolicyResponseTypeDef](./type_defs.md#lookuppolicyresponsetypedef)
- [ObjectAttributeActionTypeDef](./type_defs.md#objectattributeactiontypedef)
- [ObjectAttributeRangeTypeDef](./type_defs.md#objectattributerangetypedef)
- [ObjectAttributeUpdateTypeDef](./type_defs.md#objectattributeupdatetypedef)
- [ObjectIdentifierAndLinkNameTupleTypeDef](./type_defs.md#objectidentifierandlinknametupletypedef)
- [ObjectReferenceTypeDef](./type_defs.md#objectreferencetypedef)
- [PaginatorConfigTypeDef](./type_defs.md#paginatorconfigtypedef)
- [PathToObjectIdentifiersTypeDef](./type_defs.md#pathtoobjectidentifierstypedef)
- [PolicyAttachmentTypeDef](./type_defs.md#policyattachmenttypedef)
- [PolicyToPathTypeDef](./type_defs.md#policytopathtypedef)
- [PublishSchemaRequestRequestTypeDef](./type_defs.md#publishschemarequestrequesttypedef)
- [PublishSchemaResponseTypeDef](./type_defs.md#publishschemaresponsetypedef)
- [PutSchemaFromJsonRequestRequestTypeDef](./type_defs.md#putschemafromjsonrequestrequesttypedef)
- [PutSchemaFromJsonResponseTypeDef](./type_defs.md#putschemafromjsonresponsetypedef)
- [RemoveFacetFromObjectRequestRequestTypeDef](./type_defs.md#removefacetfromobjectrequestrequesttypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [RuleTypeDef](./type_defs.md#ruletypedef)
- [SchemaFacetTypeDef](./type_defs.md#schemafacettypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [TagTypeDef](./type_defs.md#tagtypedef)
- [TypedAttributeValueRangeTypeDef](./type_defs.md#typedattributevaluerangetypedef)
- [TypedAttributeValueTypeDef](./type_defs.md#typedattributevaluetypedef)
- [TypedLinkAttributeDefinitionTypeDef](./type_defs.md#typedlinkattributedefinitiontypedef)
- [TypedLinkAttributeRangeTypeDef](./type_defs.md#typedlinkattributerangetypedef)
- [TypedLinkFacetAttributeUpdateTypeDef](./type_defs.md#typedlinkfacetattributeupdatetypedef)
- [TypedLinkFacetTypeDef](./type_defs.md#typedlinkfacettypedef)
- [TypedLinkSchemaAndFacetNameTypeDef](./type_defs.md#typedlinkschemaandfacetnametypedef)
- [TypedLinkSpecifierTypeDef](./type_defs.md#typedlinkspecifiertypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateFacetRequestRequestTypeDef](./type_defs.md#updatefacetrequestrequesttypedef)
- [UpdateLinkAttributesRequestRequestTypeDef](./type_defs.md#updatelinkattributesrequestrequesttypedef)
- [UpdateObjectAttributesRequestRequestTypeDef](./type_defs.md#updateobjectattributesrequestrequesttypedef)
- [UpdateObjectAttributesResponseTypeDef](./type_defs.md#updateobjectattributesresponsetypedef)
- [UpdateSchemaRequestRequestTypeDef](./type_defs.md#updateschemarequestrequesttypedef)
- [UpdateSchemaResponseTypeDef](./type_defs.md#updateschemaresponsetypedef)
- [UpdateTypedLinkFacetRequestRequestTypeDef](./type_defs.md#updatetypedlinkfacetrequestrequesttypedef)
- [UpgradeAppliedSchemaRequestRequestTypeDef](./type_defs.md#upgradeappliedschemarequestrequesttypedef)
- [UpgradeAppliedSchemaResponseTypeDef](./type_defs.md#upgradeappliedschemaresponsetypedef)
- [UpgradePublishedSchemaRequestRequestTypeDef](./type_defs.md#upgradepublishedschemarequestrequesttypedef)
- [UpgradePublishedSchemaResponseTypeDef](./type_defs.md#upgradepublishedschemaresponsetypedef)
