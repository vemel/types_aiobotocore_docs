<a id="typed-dictionaries-for-aiobotocore-ram-module"></a>

# Typed dictionaries for aiobotocore RAM module

> [Index](../README.md) > [RAM](./README.md) > Typed dictionaries

Auto-generated documentation for
[RAM](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ram.html#RAM)
type annotations stubs module
[types-aiobotocore-ram](https://pypi.org/project/types-aiobotocore-ram/).

- [Typed dictionaries for aiobotocore RAM module](#typed-dictionaries-for-aiobotocore-ram-module)
  - [AcceptResourceShareInvitationRequestRequestTypeDef](#acceptresourceshareinvitationrequestrequesttypedef)
  - [AcceptResourceShareInvitationResponseTypeDef](#acceptresourceshareinvitationresponsetypedef)
  - [AssociateResourceSharePermissionRequestRequestTypeDef](#associateresourcesharepermissionrequestrequesttypedef)
  - [AssociateResourceSharePermissionResponseTypeDef](#associateresourcesharepermissionresponsetypedef)
  - [AssociateResourceShareRequestRequestTypeDef](#associateresourcesharerequestrequesttypedef)
  - [AssociateResourceShareResponseTypeDef](#associateresourceshareresponsetypedef)
  - [CreateResourceShareRequestRequestTypeDef](#createresourcesharerequestrequesttypedef)
  - [CreateResourceShareResponseTypeDef](#createresourceshareresponsetypedef)
  - [DeleteResourceShareRequestRequestTypeDef](#deleteresourcesharerequestrequesttypedef)
  - [DeleteResourceShareResponseTypeDef](#deleteresourceshareresponsetypedef)
  - [DisassociateResourceSharePermissionRequestRequestTypeDef](#disassociateresourcesharepermissionrequestrequesttypedef)
  - [DisassociateResourceSharePermissionResponseTypeDef](#disassociateresourcesharepermissionresponsetypedef)
  - [DisassociateResourceShareRequestRequestTypeDef](#disassociateresourcesharerequestrequesttypedef)
  - [DisassociateResourceShareResponseTypeDef](#disassociateresourceshareresponsetypedef)
  - [EnableSharingWithAwsOrganizationResponseTypeDef](#enablesharingwithawsorganizationresponsetypedef)
  - [GetPermissionRequestRequestTypeDef](#getpermissionrequestrequesttypedef)
  - [GetPermissionResponseTypeDef](#getpermissionresponsetypedef)
  - [GetResourcePoliciesRequestRequestTypeDef](#getresourcepoliciesrequestrequesttypedef)
  - [GetResourcePoliciesResponseTypeDef](#getresourcepoliciesresponsetypedef)
  - [GetResourceShareAssociationsRequestRequestTypeDef](#getresourceshareassociationsrequestrequesttypedef)
  - [GetResourceShareAssociationsResponseTypeDef](#getresourceshareassociationsresponsetypedef)
  - [GetResourceShareInvitationsRequestRequestTypeDef](#getresourceshareinvitationsrequestrequesttypedef)
  - [GetResourceShareInvitationsResponseTypeDef](#getresourceshareinvitationsresponsetypedef)
  - [GetResourceSharesRequestRequestTypeDef](#getresourcesharesrequestrequesttypedef)
  - [GetResourceSharesResponseTypeDef](#getresourcesharesresponsetypedef)
  - [ListPendingInvitationResourcesRequestRequestTypeDef](#listpendinginvitationresourcesrequestrequesttypedef)
  - [ListPendingInvitationResourcesResponseTypeDef](#listpendinginvitationresourcesresponsetypedef)
  - [ListPermissionVersionsRequestRequestTypeDef](#listpermissionversionsrequestrequesttypedef)
  - [ListPermissionVersionsResponseTypeDef](#listpermissionversionsresponsetypedef)
  - [ListPermissionsRequestRequestTypeDef](#listpermissionsrequestrequesttypedef)
  - [ListPermissionsResponseTypeDef](#listpermissionsresponsetypedef)
  - [ListPrincipalsRequestRequestTypeDef](#listprincipalsrequestrequesttypedef)
  - [ListPrincipalsResponseTypeDef](#listprincipalsresponsetypedef)
  - [ListResourceSharePermissionsRequestRequestTypeDef](#listresourcesharepermissionsrequestrequesttypedef)
  - [ListResourceSharePermissionsResponseTypeDef](#listresourcesharepermissionsresponsetypedef)
  - [ListResourceTypesRequestRequestTypeDef](#listresourcetypesrequestrequesttypedef)
  - [ListResourceTypesResponseTypeDef](#listresourcetypesresponsetypedef)
  - [ListResourcesRequestRequestTypeDef](#listresourcesrequestrequesttypedef)
  - [ListResourcesResponseTypeDef](#listresourcesresponsetypedef)
  - [PaginatorConfigTypeDef](#paginatorconfigtypedef)
  - [PrincipalTypeDef](#principaltypedef)
  - [PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef](#promoteresourcesharecreatedfrompolicyrequestrequesttypedef)
  - [PromoteResourceShareCreatedFromPolicyResponseTypeDef](#promoteresourcesharecreatedfrompolicyresponsetypedef)
  - [RejectResourceShareInvitationRequestRequestTypeDef](#rejectresourceshareinvitationrequestrequesttypedef)
  - [RejectResourceShareInvitationResponseTypeDef](#rejectresourceshareinvitationresponsetypedef)
  - [ResourceShareAssociationTypeDef](#resourceshareassociationtypedef)
  - [ResourceShareInvitationTypeDef](#resourceshareinvitationtypedef)
  - [ResourceSharePermissionDetailTypeDef](#resourcesharepermissiondetailtypedef)
  - [ResourceSharePermissionSummaryTypeDef](#resourcesharepermissionsummarytypedef)
  - [ResourceShareTypeDef](#resourcesharetypedef)
  - [ResourceTypeDef](#resourcetypedef)
  - [ResponseMetadataTypeDef](#responsemetadatatypedef)
  - [ServiceNameAndResourceTypeTypeDef](#servicenameandresourcetypetypedef)
  - [TagFilterTypeDef](#tagfiltertypedef)
  - [TagResourceRequestRequestTypeDef](#tagresourcerequestrequesttypedef)
  - [TagTypeDef](#tagtypedef)
  - [UntagResourceRequestRequestTypeDef](#untagresourcerequestrequesttypedef)
  - [UpdateResourceShareRequestRequestTypeDef](#updateresourcesharerequestrequesttypedef)
  - [UpdateResourceShareResponseTypeDef](#updateresourceshareresponsetypedef)

<a id="acceptresourceshareinvitationrequestrequesttypedef"></a>

## AcceptResourceShareInvitationRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import AcceptResourceShareInvitationRequestRequestTypeDef
```

Required fields:

- `resourceShareInvitationArn`: `str`

Optional fields:

- `clientToken`: `str`

<a id="acceptresourceshareinvitationresponsetypedef"></a>

## AcceptResourceShareInvitationResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import AcceptResourceShareInvitationResponseTypeDef
```

Required fields:

- `resourceShareInvitation`:
  [ResourceShareInvitationTypeDef](./type_defs.md#resourceshareinvitationtypedef)
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="associateresourcesharepermissionrequestrequesttypedef"></a>

## AssociateResourceSharePermissionRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import AssociateResourceSharePermissionRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`
- `permissionArn`: `str`

Optional fields:

- `replace`: `bool`
- `clientToken`: `str`
- `permissionVersion`: `int`

<a id="associateresourcesharepermissionresponsetypedef"></a>

## AssociateResourceSharePermissionResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import AssociateResourceSharePermissionResponseTypeDef
```

Required fields:

- `returnValue`: `bool`
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="associateresourcesharerequestrequesttypedef"></a>

## AssociateResourceShareRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import AssociateResourceShareRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

Optional fields:

- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `clientToken`: `str`

<a id="associateresourceshareresponsetypedef"></a>

## AssociateResourceShareResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import AssociateResourceShareResponseTypeDef
```

Required fields:

- `resourceShareAssociations`:
  `List`\[[ResourceShareAssociationTypeDef](./type_defs.md#resourceshareassociationtypedef)\]
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="createresourcesharerequestrequesttypedef"></a>

## CreateResourceShareRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import CreateResourceShareRequestRequestTypeDef
```

Required fields:

- `name`: `str`

Optional fields:

- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `allowExternalPrincipals`: `bool`
- `clientToken`: `str`
- `permissionArns`: `Sequence`\[`str`\]

<a id="createresourceshareresponsetypedef"></a>

## CreateResourceShareResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import CreateResourceShareResponseTypeDef
```

Required fields:

- `resourceShare`: [ResourceShareTypeDef](./type_defs.md#resourcesharetypedef)
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="deleteresourcesharerequestrequesttypedef"></a>

## DeleteResourceShareRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import DeleteResourceShareRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

Optional fields:

- `clientToken`: `str`

<a id="deleteresourceshareresponsetypedef"></a>

## DeleteResourceShareResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import DeleteResourceShareResponseTypeDef
```

Required fields:

- `returnValue`: `bool`
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociateresourcesharepermissionrequestrequesttypedef"></a>

## DisassociateResourceSharePermissionRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import DisassociateResourceSharePermissionRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`
- `permissionArn`: `str`

Optional fields:

- `clientToken`: `str`

<a id="disassociateresourcesharepermissionresponsetypedef"></a>

## DisassociateResourceSharePermissionResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import DisassociateResourceSharePermissionResponseTypeDef
```

Required fields:

- `returnValue`: `bool`
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="disassociateresourcesharerequestrequesttypedef"></a>

## DisassociateResourceShareRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import DisassociateResourceShareRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

Optional fields:

- `resourceArns`: `Sequence`\[`str`\]
- `principals`: `Sequence`\[`str`\]
- `clientToken`: `str`

<a id="disassociateresourceshareresponsetypedef"></a>

## DisassociateResourceShareResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import DisassociateResourceShareResponseTypeDef
```

Required fields:

- `resourceShareAssociations`:
  `List`\[[ResourceShareAssociationTypeDef](./type_defs.md#resourceshareassociationtypedef)\]
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="enablesharingwithawsorganizationresponsetypedef"></a>

## EnableSharingWithAwsOrganizationResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import EnableSharingWithAwsOrganizationResponseTypeDef
```

Required fields:

- `returnValue`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getpermissionrequestrequesttypedef"></a>

## GetPermissionRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import GetPermissionRequestRequestTypeDef
```

Required fields:

- `permissionArn`: `str`

Optional fields:

- `permissionVersion`: `int`

<a id="getpermissionresponsetypedef"></a>

## GetPermissionResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import GetPermissionResponseTypeDef
```

Required fields:

- `permission`:
  [ResourceSharePermissionDetailTypeDef](./type_defs.md#resourcesharepermissiondetailtypedef)
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getresourcepoliciesrequestrequesttypedef"></a>

## GetResourcePoliciesRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourcePoliciesRequestRequestTypeDef
```

Required fields:

- `resourceArns`: `Sequence`\[`str`\]

Optional fields:

- `principal`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

<a id="getresourcepoliciesresponsetypedef"></a>

## GetResourcePoliciesResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourcePoliciesResponseTypeDef
```

Required fields:

- `policies`: `List`\[`str`\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getresourceshareassociationsrequestrequesttypedef"></a>

## GetResourceShareAssociationsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceShareAssociationsRequestRequestTypeDef
```

Required fields:

- `associationType`:
  [ResourceShareAssociationTypeType](./literals.md#resourceshareassociationtypetype)

Optional fields:

- `resourceShareArns`: `Sequence`\[`str`\]
- `resourceArn`: `str`
- `principal`: `str`
- `associationStatus`:
  [ResourceShareAssociationStatusType](./literals.md#resourceshareassociationstatustype)
- `nextToken`: `str`
- `maxResults`: `int`

<a id="getresourceshareassociationsresponsetypedef"></a>

## GetResourceShareAssociationsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceShareAssociationsResponseTypeDef
```

Required fields:

- `resourceShareAssociations`:
  `List`\[[ResourceShareAssociationTypeDef](./type_defs.md#resourceshareassociationtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getresourceshareinvitationsrequestrequesttypedef"></a>

## GetResourceShareInvitationsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceShareInvitationsRequestRequestTypeDef
```

Optional fields:

- `resourceShareInvitationArns`: `Sequence`\[`str`\]
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

<a id="getresourceshareinvitationsresponsetypedef"></a>

## GetResourceShareInvitationsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceShareInvitationsResponseTypeDef
```

Required fields:

- `resourceShareInvitations`:
  `List`\[[ResourceShareInvitationTypeDef](./type_defs.md#resourceshareinvitationtypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="getresourcesharesrequestrequesttypedef"></a>

## GetResourceSharesRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceSharesRequestRequestTypeDef
```

Required fields:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)

Optional fields:

- `resourceShareArns`: `Sequence`\[`str`\]
- `resourceShareStatus`:
  [ResourceShareStatusType](./literals.md#resourcesharestatustype)
- `name`: `str`
- `tagFilters`:
  `Sequence`\[[TagFilterTypeDef](./type_defs.md#tagfiltertypedef)\]
- `nextToken`: `str`
- `maxResults`: `int`
- `permissionArn`: `str`

<a id="getresourcesharesresponsetypedef"></a>

## GetResourceSharesResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import GetResourceSharesResponseTypeDef
```

Required fields:

- `resourceShares`:
  `List`\[[ResourceShareTypeDef](./type_defs.md#resourcesharetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpendinginvitationresourcesrequestrequesttypedef"></a>

## ListPendingInvitationResourcesRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPendingInvitationResourcesRequestRequestTypeDef
```

Required fields:

- `resourceShareInvitationArn`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

<a id="listpendinginvitationresourcesresponsetypedef"></a>

## ListPendingInvitationResourcesResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPendingInvitationResourcesResponseTypeDef
```

Required fields:

- `resources`: `List`\[[ResourceTypeDef](./type_defs.md#resourcetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpermissionversionsrequestrequesttypedef"></a>

## ListPermissionVersionsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPermissionVersionsRequestRequestTypeDef
```

Required fields:

- `permissionArn`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listpermissionversionsresponsetypedef"></a>

## ListPermissionVersionsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPermissionVersionsResponseTypeDef
```

Required fields:

- `permissions`:
  `List`\[[ResourceSharePermissionSummaryTypeDef](./type_defs.md#resourcesharepermissionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listpermissionsrequestrequesttypedef"></a>

## ListPermissionsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPermissionsRequestRequestTypeDef
```

Optional fields:

- `resourceType`: `str`
- `nextToken`: `str`
- `maxResults`: `int`

<a id="listpermissionsresponsetypedef"></a>

## ListPermissionsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPermissionsResponseTypeDef
```

Required fields:

- `permissions`:
  `List`\[[ResourceSharePermissionSummaryTypeDef](./type_defs.md#resourcesharepermissionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listprincipalsrequestrequesttypedef"></a>

## ListPrincipalsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPrincipalsRequestRequestTypeDef
```

Required fields:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)

Optional fields:

- `resourceArn`: `str`
- `principals`: `Sequence`\[`str`\]
- `resourceType`: `str`
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`

<a id="listprincipalsresponsetypedef"></a>

## ListPrincipalsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListPrincipalsResponseTypeDef
```

Required fields:

- `principals`: `List`\[[PrincipalTypeDef](./type_defs.md#principaltypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listresourcesharepermissionsrequestrequesttypedef"></a>

## ListResourceSharePermissionsRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourceSharePermissionsRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`

<a id="listresourcesharepermissionsresponsetypedef"></a>

## ListResourceSharePermissionsResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourceSharePermissionsResponseTypeDef
```

Required fields:

- `permissions`:
  `List`\[[ResourceSharePermissionSummaryTypeDef](./type_defs.md#resourcesharepermissionsummarytypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listresourcetypesrequestrequesttypedef"></a>

## ListResourceTypesRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourceTypesRequestRequestTypeDef
```

Optional fields:

- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

<a id="listresourcetypesresponsetypedef"></a>

## ListResourceTypesResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourceTypesResponseTypeDef
```

Required fields:

- `resourceTypes`:
  `List`\[[ServiceNameAndResourceTypeTypeDef](./type_defs.md#servicenameandresourcetypetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="listresourcesrequestrequesttypedef"></a>

## ListResourcesRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourcesRequestRequestTypeDef
```

Required fields:

- `resourceOwner`: [ResourceOwnerType](./literals.md#resourceownertype)

Optional fields:

- `principal`: `str`
- `resourceType`: `str`
- `resourceArns`: `Sequence`\[`str`\]
- `resourceShareArns`: `Sequence`\[`str`\]
- `nextToken`: `str`
- `maxResults`: `int`
- `resourceRegionScope`:
  [ResourceRegionScopeFilterType](./literals.md#resourceregionscopefiltertype)

<a id="listresourcesresponsetypedef"></a>

## ListResourcesResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import ListResourcesResponseTypeDef
```

Required fields:

- `resources`: `List`\[[ResourceTypeDef](./type_defs.md#resourcetypedef)\]
- `nextToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="paginatorconfigtypedef"></a>

## PaginatorConfigTypeDef

```python
from types_aiobotocore_ram.type_defs import PaginatorConfigTypeDef
```

Optional fields:

- `MaxItems`: `int`
- `PageSize`: `int`
- `StartingToken`: `str`

<a id="principaltypedef"></a>

## PrincipalTypeDef

```python
from types_aiobotocore_ram.type_defs import PrincipalTypeDef
```

Optional fields:

- `id`: `str`
- `resourceShareArn`: `str`
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `external`: `bool`

<a id="promoteresourcesharecreatedfrompolicyrequestrequesttypedef"></a>

## PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import PromoteResourceShareCreatedFromPolicyRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

<a id="promoteresourcesharecreatedfrompolicyresponsetypedef"></a>

## PromoteResourceShareCreatedFromPolicyResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import PromoteResourceShareCreatedFromPolicyResponseTypeDef
```

Required fields:

- `returnValue`: `bool`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="rejectresourceshareinvitationrequestrequesttypedef"></a>

## RejectResourceShareInvitationRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import RejectResourceShareInvitationRequestRequestTypeDef
```

Required fields:

- `resourceShareInvitationArn`: `str`

Optional fields:

- `clientToken`: `str`

<a id="rejectresourceshareinvitationresponsetypedef"></a>

## RejectResourceShareInvitationResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import RejectResourceShareInvitationResponseTypeDef
```

Required fields:

- `resourceShareInvitation`:
  [ResourceShareInvitationTypeDef](./type_defs.md#resourceshareinvitationtypedef)
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)

<a id="resourceshareassociationtypedef"></a>

## ResourceShareAssociationTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceShareAssociationTypeDef
```

Optional fields:

- `resourceShareArn`: `str`
- `resourceShareName`: `str`
- `associatedEntity`: `str`
- `associationType`:
  [ResourceShareAssociationTypeType](./literals.md#resourceshareassociationtypetype)
- `status`:
  [ResourceShareAssociationStatusType](./literals.md#resourceshareassociationstatustype)
- `statusMessage`: `str`
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `external`: `bool`

<a id="resourceshareinvitationtypedef"></a>

## ResourceShareInvitationTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceShareInvitationTypeDef
```

Optional fields:

- `resourceShareInvitationArn`: `str`
- `resourceShareName`: `str`
- `resourceShareArn`: `str`
- `senderAccountId`: `str`
- `receiverAccountId`: `str`
- `invitationTimestamp`: `datetime`
- `status`:
  [ResourceShareInvitationStatusType](./literals.md#resourceshareinvitationstatustype)
- `resourceShareAssociations`:
  `List`\[[ResourceShareAssociationTypeDef](./type_defs.md#resourceshareassociationtypedef)\]
- `receiverArn`: `str`

<a id="resourcesharepermissiondetailtypedef"></a>

## ResourceSharePermissionDetailTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceSharePermissionDetailTypeDef
```

Optional fields:

- `arn`: `str`
- `version`: `str`
- `defaultVersion`: `bool`
- `name`: `str`
- `resourceType`: `str`
- `permission`: `str`
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `isResourceTypeDefault`: `bool`

<a id="resourcesharepermissionsummarytypedef"></a>

## ResourceSharePermissionSummaryTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceSharePermissionSummaryTypeDef
```

Optional fields:

- `arn`: `str`
- `version`: `str`
- `defaultVersion`: `bool`
- `name`: `str`
- `resourceType`: `str`
- `status`: `str`
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `isResourceTypeDefault`: `bool`

<a id="resourcesharetypedef"></a>

## ResourceShareTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceShareTypeDef
```

Optional fields:

- `resourceShareArn`: `str`
- `name`: `str`
- `owningAccountId`: `str`
- `allowExternalPrincipals`: `bool`
- `status`: [ResourceShareStatusType](./literals.md#resourcesharestatustype)
- `statusMessage`: `str`
- `tags`: `List`\[[TagTypeDef](./type_defs.md#tagtypedef)\]
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `featureSet`:
  [ResourceShareFeatureSetType](./literals.md#resourcesharefeaturesettype)

<a id="resourcetypedef"></a>

## ResourceTypeDef

```python
from types_aiobotocore_ram.type_defs import ResourceTypeDef
```

Optional fields:

- `arn`: `str`
- `type`: `str`
- `resourceShareArn`: `str`
- `resourceGroupArn`: `str`
- `status`: [ResourceStatusType](./literals.md#resourcestatustype)
- `statusMessage`: `str`
- `creationTime`: `datetime`
- `lastUpdatedTime`: `datetime`
- `resourceRegionScope`:
  [ResourceRegionScopeType](./literals.md#resourceregionscopetype)

<a id="responsemetadatatypedef"></a>

## ResponseMetadataTypeDef

```python
from types_aiobotocore_ram.type_defs import ResponseMetadataTypeDef
```

Required fields:

- `RequestId`: `str`
- `HostId`: `str`
- `HTTPStatusCode`: `int`
- `HTTPHeaders`: `Dict`\[`str`, `str`\]
- `RetryAttempts`: `int`

<a id="servicenameandresourcetypetypedef"></a>

## ServiceNameAndResourceTypeTypeDef

```python
from types_aiobotocore_ram.type_defs import ServiceNameAndResourceTypeTypeDef
```

Optional fields:

- `resourceType`: `str`
- `serviceName`: `str`
- `resourceRegionScope`:
  [ResourceRegionScopeType](./literals.md#resourceregionscopetype)

<a id="tagfiltertypedef"></a>

## TagFilterTypeDef

```python
from types_aiobotocore_ram.type_defs import TagFilterTypeDef
```

Optional fields:

- `tagKey`: `str`
- `tagValues`: `Sequence`\[`str`\]

<a id="tagresourcerequestrequesttypedef"></a>

## TagResourceRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import TagResourceRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`
- `tags`: `Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]

<a id="tagtypedef"></a>

## TagTypeDef

```python
from types_aiobotocore_ram.type_defs import TagTypeDef
```

Optional fields:

- `key`: `str`
- `value`: `str`

<a id="untagresourcerequestrequesttypedef"></a>

## UntagResourceRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import UntagResourceRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`
- `tagKeys`: `Sequence`\[`str`\]

<a id="updateresourcesharerequestrequesttypedef"></a>

## UpdateResourceShareRequestRequestTypeDef

```python
from types_aiobotocore_ram.type_defs import UpdateResourceShareRequestRequestTypeDef
```

Required fields:

- `resourceShareArn`: `str`

Optional fields:

- `name`: `str`
- `allowExternalPrincipals`: `bool`
- `clientToken`: `str`

<a id="updateresourceshareresponsetypedef"></a>

## UpdateResourceShareResponseTypeDef

```python
from types_aiobotocore_ram.type_defs import UpdateResourceShareResponseTypeDef
```

Required fields:

- `resourceShare`: [ResourceShareTypeDef](./type_defs.md#resourcesharetypedef)
- `clientToken`: `str`
- `ResponseMetadata`:
  [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
