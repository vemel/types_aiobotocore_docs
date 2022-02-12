<a id="type-annotations-for-aiobotocore-managedblockchain-module"></a>

# Type annotations for aiobotocore ManagedBlockchain module

> [Index](..) > ManagedBlockchain

Auto-generated documentation for
[ManagedBlockchain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/managedblockchain.html#ManagedBlockchain)
type annotations stubs module
[types-aiobotocore-managedblockchain](https://pypi.org/project/types-aiobotocore-managedblockchain/).

- [Type annotations for aiobotocore ManagedBlockchain module](#type-annotations-for-aiobotocore-managedblockchain-module)
  - [How to install](#how-to-install)
    - [VSCode extension](#vscode-extension)
    - [From PyPI with pip](#from-pypi-with-pip)
  - [How to uninstall](#how-to-uninstall)
  - [ManagedBlockchainClient](#managedblockchainclient)
    - [Methods](#methods)
    - [Exceptions](#exceptions)
  - [Literals](#literals)
  - [Typed dictionaries](#typed-dictionaries)

<a id="how-to-install"></a>

## How to install

<a id="vscode-extension"></a>

### VSCode extension

Add
[AWS Boto3](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide)
extension to your VSCode and run `AWS boto3: Quick Start` command.

Click `Modify` and select `boto3 common` and `ManagedBlockchain`.

<a id="from-pypi-with-pip"></a>

### From PyPI with pip

Install `types-aiobotocore` for `ManagedBlockchain` service.

```bash
# install with aiobotocore type annotations
python -m pip install 'types-aiobotocore[managedblockchain]'

# Lite version does not provide session.client/resource overloads
# it is more RAM-friendly, but requires explicit type annotations
python -m pip install 'types-aiobotocore-lite[managedblockchain]'

# standalone installation
python -m pip install types-aiobotocore-managedblockchain
```

<a id="how-to-uninstall"></a>

## How to uninstall

```bash
python -m pip uninstall -y types-aiobotocore-managedblockchain
```

<a id="managedblockchainclient"></a>

## ManagedBlockchainClient

Type annotations for `session.create_client("managedblockchain")` as
[ManagedBlockchainClient](./client.md)

Can be used directly:

```python
from types_aiobotocore_managedblockchain.client import ManagedBlockchainClient
```

<a id="methods"></a>

### Methods

- [__aenter__](./client.md#__aenter__)
- [__aexit__](./client.md#__aexit__)
- [can_paginate](./client.md#can_paginate)
- [create_member](./client.md#create_member)
- [create_network](./client.md#create_network)
- [create_node](./client.md#create_node)
- [create_proposal](./client.md#create_proposal)
- [delete_member](./client.md#delete_member)
- [delete_node](./client.md#delete_node)
- [exceptions](./client.md#exceptions)
- [generate_presigned_url](./client.md#generate_presigned_url)
- [get_member](./client.md#get_member)
- [get_network](./client.md#get_network)
- [get_node](./client.md#get_node)
- [get_proposal](./client.md#get_proposal)
- [list_invitations](./client.md#list_invitations)
- [list_members](./client.md#list_members)
- [list_networks](./client.md#list_networks)
- [list_nodes](./client.md#list_nodes)
- [list_proposal_votes](./client.md#list_proposal_votes)
- [list_proposals](./client.md#list_proposals)
- [list_tags_for_resource](./client.md#list_tags_for_resource)
- [reject_invitation](./client.md#reject_invitation)
- [tag_resource](./client.md#tag_resource)
- [untag_resource](./client.md#untag_resource)
- [update_member](./client.md#update_member)
- [update_node](./client.md#update_node)
- [vote_on_proposal](./client.md#vote_on_proposal)

<a id="exceptions"></a>

### Exceptions

ManagedBlockchainClient [exceptions](./client.md#exceptions)

- AccessDeniedException
- ClientError
- IllegalActionException
- InternalServiceErrorException
- InvalidRequestException
- ResourceAlreadyExistsException
- ResourceLimitExceededException
- ResourceNotFoundException
- ResourceNotReadyException
- ThrottlingException
- TooManyTagsException

<a id="literals"></a>

## Literals

Type annotations for [literals](./literals.md) used in methods and schema.

Can be used directly:

```python
from types_aiobotocore_managedblockchain.literals import EditionType, ...
```

- [EditionType](./literals.md#editiontype)
- [FrameworkType](./literals.md#frameworktype)
- [InvitationStatusType](./literals.md#invitationstatustype)
- [MemberStatusType](./literals.md#memberstatustype)
- [NetworkStatusType](./literals.md#networkstatustype)
- [NodeStatusType](./literals.md#nodestatustype)
- [ProposalStatusType](./literals.md#proposalstatustype)
- [StateDBTypeType](./literals.md#statedbtypetype)
- [ThresholdComparatorType](./literals.md#thresholdcomparatortype)
- [VoteValueType](./literals.md#votevaluetype)
- [ServiceName](./literals.md#servicename)

<a id="typed-dictionaries"></a>

## Typed dictionaries

Type annotations for [typed dictionaries](./type_defs.md) used in methods and
schema.

Can be used directly:

```python
from mypy_boto3_managedblockchain.type_defs import ApprovalThresholdPolicyTypeDef, ...
```

- [ApprovalThresholdPolicyTypeDef](./type_defs.md#approvalthresholdpolicytypedef)
- [CreateMemberInputRequestTypeDef](./type_defs.md#creatememberinputrequesttypedef)
- [CreateMemberOutputTypeDef](./type_defs.md#creatememberoutputtypedef)
- [CreateNetworkInputRequestTypeDef](./type_defs.md#createnetworkinputrequesttypedef)
- [CreateNetworkOutputTypeDef](./type_defs.md#createnetworkoutputtypedef)
- [CreateNodeInputRequestTypeDef](./type_defs.md#createnodeinputrequesttypedef)
- [CreateNodeOutputTypeDef](./type_defs.md#createnodeoutputtypedef)
- [CreateProposalInputRequestTypeDef](./type_defs.md#createproposalinputrequesttypedef)
- [CreateProposalOutputTypeDef](./type_defs.md#createproposaloutputtypedef)
- [DeleteMemberInputRequestTypeDef](./type_defs.md#deletememberinputrequesttypedef)
- [DeleteNodeInputRequestTypeDef](./type_defs.md#deletenodeinputrequesttypedef)
- [GetMemberInputRequestTypeDef](./type_defs.md#getmemberinputrequesttypedef)
- [GetMemberOutputTypeDef](./type_defs.md#getmemberoutputtypedef)
- [GetNetworkInputRequestTypeDef](./type_defs.md#getnetworkinputrequesttypedef)
- [GetNetworkOutputTypeDef](./type_defs.md#getnetworkoutputtypedef)
- [GetNodeInputRequestTypeDef](./type_defs.md#getnodeinputrequesttypedef)
- [GetNodeOutputTypeDef](./type_defs.md#getnodeoutputtypedef)
- [GetProposalInputRequestTypeDef](./type_defs.md#getproposalinputrequesttypedef)
- [GetProposalOutputTypeDef](./type_defs.md#getproposaloutputtypedef)
- [InvitationTypeDef](./type_defs.md#invitationtypedef)
- [InviteActionTypeDef](./type_defs.md#inviteactiontypedef)
- [ListInvitationsInputRequestTypeDef](./type_defs.md#listinvitationsinputrequesttypedef)
- [ListInvitationsOutputTypeDef](./type_defs.md#listinvitationsoutputtypedef)
- [ListMembersInputRequestTypeDef](./type_defs.md#listmembersinputrequesttypedef)
- [ListMembersOutputTypeDef](./type_defs.md#listmembersoutputtypedef)
- [ListNetworksInputRequestTypeDef](./type_defs.md#listnetworksinputrequesttypedef)
- [ListNetworksOutputTypeDef](./type_defs.md#listnetworksoutputtypedef)
- [ListNodesInputRequestTypeDef](./type_defs.md#listnodesinputrequesttypedef)
- [ListNodesOutputTypeDef](./type_defs.md#listnodesoutputtypedef)
- [ListProposalVotesInputRequestTypeDef](./type_defs.md#listproposalvotesinputrequesttypedef)
- [ListProposalVotesOutputTypeDef](./type_defs.md#listproposalvotesoutputtypedef)
- [ListProposalsInputRequestTypeDef](./type_defs.md#listproposalsinputrequesttypedef)
- [ListProposalsOutputTypeDef](./type_defs.md#listproposalsoutputtypedef)
- [ListTagsForResourceRequestRequestTypeDef](./type_defs.md#listtagsforresourcerequestrequesttypedef)
- [ListTagsForResourceResponseTypeDef](./type_defs.md#listtagsforresourceresponsetypedef)
- [LogConfigurationTypeDef](./type_defs.md#logconfigurationtypedef)
- [LogConfigurationsTypeDef](./type_defs.md#logconfigurationstypedef)
- [MemberConfigurationTypeDef](./type_defs.md#memberconfigurationtypedef)
- [MemberFabricAttributesTypeDef](./type_defs.md#memberfabricattributestypedef)
- [MemberFabricConfigurationTypeDef](./type_defs.md#memberfabricconfigurationtypedef)
- [MemberFabricLogPublishingConfigurationTypeDef](./type_defs.md#memberfabriclogpublishingconfigurationtypedef)
- [MemberFrameworkAttributesTypeDef](./type_defs.md#memberframeworkattributestypedef)
- [MemberFrameworkConfigurationTypeDef](./type_defs.md#memberframeworkconfigurationtypedef)
- [MemberLogPublishingConfigurationTypeDef](./type_defs.md#memberlogpublishingconfigurationtypedef)
- [MemberSummaryTypeDef](./type_defs.md#membersummarytypedef)
- [MemberTypeDef](./type_defs.md#membertypedef)
- [NetworkEthereumAttributesTypeDef](./type_defs.md#networkethereumattributestypedef)
- [NetworkFabricAttributesTypeDef](./type_defs.md#networkfabricattributestypedef)
- [NetworkFabricConfigurationTypeDef](./type_defs.md#networkfabricconfigurationtypedef)
- [NetworkFrameworkAttributesTypeDef](./type_defs.md#networkframeworkattributestypedef)
- [NetworkFrameworkConfigurationTypeDef](./type_defs.md#networkframeworkconfigurationtypedef)
- [NetworkSummaryTypeDef](./type_defs.md#networksummarytypedef)
- [NetworkTypeDef](./type_defs.md#networktypedef)
- [NodeConfigurationTypeDef](./type_defs.md#nodeconfigurationtypedef)
- [NodeEthereumAttributesTypeDef](./type_defs.md#nodeethereumattributestypedef)
- [NodeFabricAttributesTypeDef](./type_defs.md#nodefabricattributestypedef)
- [NodeFabricLogPublishingConfigurationTypeDef](./type_defs.md#nodefabriclogpublishingconfigurationtypedef)
- [NodeFrameworkAttributesTypeDef](./type_defs.md#nodeframeworkattributestypedef)
- [NodeLogPublishingConfigurationTypeDef](./type_defs.md#nodelogpublishingconfigurationtypedef)
- [NodeSummaryTypeDef](./type_defs.md#nodesummarytypedef)
- [NodeTypeDef](./type_defs.md#nodetypedef)
- [ProposalActionsTypeDef](./type_defs.md#proposalactionstypedef)
- [ProposalSummaryTypeDef](./type_defs.md#proposalsummarytypedef)
- [ProposalTypeDef](./type_defs.md#proposaltypedef)
- [RejectInvitationInputRequestTypeDef](./type_defs.md#rejectinvitationinputrequesttypedef)
- [RemoveActionTypeDef](./type_defs.md#removeactiontypedef)
- [ResponseMetadataTypeDef](./type_defs.md#responsemetadatatypedef)
- [TagResourceRequestRequestTypeDef](./type_defs.md#tagresourcerequestrequesttypedef)
- [UntagResourceRequestRequestTypeDef](./type_defs.md#untagresourcerequestrequesttypedef)
- [UpdateMemberInputRequestTypeDef](./type_defs.md#updatememberinputrequesttypedef)
- [UpdateNodeInputRequestTypeDef](./type_defs.md#updatenodeinputrequesttypedef)
- [VoteOnProposalInputRequestTypeDef](./type_defs.md#voteonproposalinputrequesttypedef)
- [VoteSummaryTypeDef](./type_defs.md#votesummarytypedef)
- [VotingPolicyTypeDef](./type_defs.md#votingpolicytypedef)
