---
class_count: 33
classes:
- CancelChangeSetRequest
- CancelChangeSetResponse
- Change
- ChangeSetSummaryListItem
- ChangeSummary
- DeleteResourcePolicyRequest
- DeleteResourcePolicyResponse
- DescribeChangeSetRequest
- DescribeChangeSetResponse
- DescribeEntityRequest
- DescribeEntityResponse
- Entity
- EntitySummary
- ErrorDetail
- Filter
- GetResourcePolicyRequest
- GetResourcePolicyResponse
- ListChangeSetsRequest
- ListChangeSetsResponse
- ListEntitiesRequest
- ListEntitiesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- PutResourcePolicyRequest
- PutResourcePolicyResponse
- Sort
- StartChangeSetRequest
- StartChangeSetResponse
- Tag
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
context_file: json-ld/amazon-marketplace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/json-ld/amazon-marketplace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Marketplace from Amazon Marketplace.
layout: jsonld
name: Amazon Marketplace Context
namespaces:
- prefix: amkt
  uri: https://amkt.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Catalog
  type: ''
- container: ''
  name: ChangeName
  type: ''
- container: ''
  name: ChangeSet
  type: ''
- container: ''
  name: ChangeSetArn
  type: ''
- container: ''
  name: ChangeSetId
  type: ''
- container: ''
  name: ChangeSetName
  type: ''
- container: ''
  name: ChangeSetSummaryList
  type: ''
- container: ''
  name: ChangeSetTags
  type: ''
- container: ''
  name: ChangeType
  type: ''
- container: ''
  name: ClientRequestToken
  type: ''
- container: ''
  name: Details
  type: ''
- container: ''
  name: EndTime
  type: ''
- container: ''
  name: EntityArn
  type: ''
- container: ''
  name: EntityId
  type: ''
- container: ''
  name: EntityIdList
  type: ''
- container: ''
  name: EntityIdentifier
  type: ''
- container: ''
  name: EntitySummaryList
  type: ''
- container: ''
  name: EntityTags
  type: ''
- container: ''
  name: EntityType
  type: ''
- container: ''
  name: ErrorCode
  type: ''
- container: ''
  name: ErrorDetailList
  type: ''
- container: ''
  name: ErrorMessage
  type: ''
- container: ''
  name: FailureCode
  type: ''
- container: ''
  name: FailureDescription
  type: ''
- container: ''
  name: FilterList
  type: ''
- container: ''
  name: Identifier
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: LastModifiedDate
  type: ''
- container: ''
  name: MaxResults
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: OwnershipType
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: ResourceArn
  type: ''
- container: ''
  name: SortBy
  type: ''
- container: ''
  name: SortOrder
  type: ''
- container: ''
  name: StartTime
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: TagKeys
  type: ''
- container: ''
  name: Tags
  type: ''
- container: ''
  name: Type
  type: ''
- container: ''
  name: Value
  type: ''
- container: ''
  name: ValueList
  type: ''
- container: ''
  name: Visibility
  type: ''
property_count: 44
provider_name: Amazon Marketplace
provider_slug: amazon-marketplace
slug: amazon-marketplace-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amkt\": \"https://amkt.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CancelChangeSetRequest\": \"amkt:CancelChangeSetRequest\",\n    \"CancelChangeSetResponse\": \"amkt:CancelChangeSetResponse\",\n    \"Change\": \"amkt:Change\",\n    \"ChangeSetSummaryListItem\": \"amkt:ChangeSetSummaryListItem\",\n    \"ChangeSummary\": \"amkt:ChangeSummary\",\n    \"DeleteResourcePolicyRequest\": \"amkt:DeleteResourcePolicyRequest\",\n    \"DeleteResourcePolicyResponse\": \"amkt:DeleteResourcePolicyResponse\",\n    \"DescribeChangeSetRequest\": \"amkt:DescribeChangeSetRequest\",\n    \"DescribeChangeSetResponse\": \"amkt:DescribeChangeSetResponse\",\n    \"DescribeEntityRequest\": \"amkt:DescribeEntityRequest\",\n    \"DescribeEntityResponse\": \"amkt:DescribeEntityResponse\",\n    \"Entity\": \"amkt:Entity\",\n    \"EntitySummary\": \"amkt:EntitySummary\"\
  ,\n    \"ErrorDetail\": \"amkt:ErrorDetail\",\n    \"Filter\": \"amkt:Filter\",\n    \"GetResourcePolicyRequest\": \"amkt:GetResourcePolicyRequest\",\n    \"GetResourcePolicyResponse\": \"amkt:GetResourcePolicyResponse\",\n    \"ListChangeSetsRequest\": \"amkt:ListChangeSetsRequest\",\n    \"ListChangeSetsResponse\": \"amkt:ListChangeSetsResponse\",\n    \"ListEntitiesRequest\": \"amkt:ListEntitiesRequest\",\n    \"ListEntitiesResponse\": \"amkt:ListEntitiesResponse\",\n    \"ListTagsForResourceRequest\": \"amkt:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amkt:ListTagsForResourceResponse\",\n    \"PutResourcePolicyRequest\": \"amkt:PutResourcePolicyRequest\",\n    \"PutResourcePolicyResponse\": \"amkt:PutResourcePolicyResponse\",\n    \"Sort\": \"amkt:Sort\",\n    \"StartChangeSetRequest\": \"amkt:StartChangeSetRequest\",\n    \"StartChangeSetResponse\": \"amkt:StartChangeSetResponse\",\n    \"Tag\": \"amkt:Tag\",\n    \"TagResourceRequest\": \"amkt:TagResourceRequest\"\
  ,\n    \"TagResourceResponse\": \"amkt:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amkt:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amkt:UntagResourceResponse\",\n    \"Catalog\": {\n      \"@id\": \"amkt:Catalog\"\n    },\n    \"ChangeName\": {\n      \"@id\": \"amkt:ChangeName\"\n    },\n    \"ChangeSet\": {\n      \"@id\": \"amkt:ChangeSet\"\n    },\n    \"ChangeSetArn\": {\n      \"@id\": \"amkt:ChangeSetArn\"\n    },\n    \"ChangeSetId\": {\n      \"@id\": \"amkt:ChangeSetId\"\n    },\n    \"ChangeSetName\": {\n      \"@id\": \"amkt:ChangeSetName\"\n    },\n    \"ChangeSetSummaryList\": {\n      \"@id\": \"amkt:ChangeSetSummaryList\"\n    },\n    \"ChangeSetTags\": {\n      \"@id\": \"amkt:ChangeSetTags\"\n    },\n    \"ChangeType\": {\n      \"@id\": \"amkt:ChangeType\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"amkt:ClientRequestToken\"\n    },\n    \"Details\": {\n      \"@id\": \"amkt:Details\"\n    },\n    \"EndTime\": {\n      \"@id\"\
  : \"amkt:EndTime\"\n    },\n    \"EntityArn\": {\n      \"@id\": \"amkt:EntityArn\"\n    },\n    \"EntityId\": {\n      \"@id\": \"amkt:EntityId\"\n    },\n    \"EntityIdList\": {\n      \"@id\": \"amkt:EntityIdList\"\n    },\n    \"EntityIdentifier\": {\n      \"@id\": \"amkt:EntityIdentifier\"\n    },\n    \"EntitySummaryList\": {\n      \"@id\": \"amkt:EntitySummaryList\"\n    },\n    \"EntityTags\": {\n      \"@id\": \"amkt:EntityTags\"\n    },\n    \"EntityType\": {\n      \"@id\": \"amkt:EntityType\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"amkt:ErrorCode\"\n    },\n    \"ErrorDetailList\": {\n      \"@id\": \"amkt:ErrorDetailList\"\n    },\n    \"ErrorMessage\": {\n      \"@id\": \"amkt:ErrorMessage\"\n    },\n    \"FailureCode\": {\n      \"@id\": \"amkt:FailureCode\"\n    },\n    \"FailureDescription\": {\n      \"@id\": \"amkt:FailureDescription\"\n    },\n    \"FilterList\": {\n      \"@id\": \"amkt:FilterList\"\n    },\n    \"Identifier\": {\n      \"@id\": \"amkt:Identifier\"\
  \n    },\n    \"Key\": {\n      \"@id\": \"amkt:Key\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"amkt:LastModifiedDate\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"amkt:MaxResults\"\n    },\n    \"Name\": {\n      \"@id\": \"amkt:Name\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amkt:NextToken\"\n    },\n    \"OwnershipType\": {\n      \"@id\": \"amkt:OwnershipType\"\n    },\n    \"Policy\": {\n      \"@id\": \"amkt:Policy\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"amkt:ResourceArn\"\n    },\n    \"SortBy\": {\n      \"@id\": \"amkt:SortBy\"\n    },\n    \"SortOrder\": {\n      \"@id\": \"amkt:SortOrder\"\n    },\n    \"StartTime\": {\n      \"@id\": \"amkt:StartTime\"\n    },\n    \"Status\": {\n      \"@id\": \"amkt:Status\"\n    },\n    \"TagKeys\": {\n      \"@id\": \"amkt:TagKeys\"\n    },\n    \"Tags\": {\n      \"@id\": \"amkt:Tags\"\n    },\n    \"Type\": {\n      \"@id\": \"amkt:Type\"\n    },\n    \"Value\": {\n      \"@id\": \"amkt:Value\"\n \
  \   },\n    \"ValueList\": {\n      \"@id\": \"amkt:ValueList\"\n    },\n    \"Visibility\": {\n      \"@id\": \"amkt:Visibility\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/json-ld/amazon-marketplace-context.jsonld
tags:
- AWS
- Commerce
- ISV
- Marketplace
- Software Catalog
- JSON-LD
- Linked Data
- Semantic Web
---
