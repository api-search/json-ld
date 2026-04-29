---
class_count: 0
classes: []
context_file: json-ld/hubspot-blog-posts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-blog-posts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Blog Posts from HubSpot.
layout: jsonld
name: Hubspot Blog Posts Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: BlogPost
  type: ''
- container: ''
  name: BlogPostInput
  type: ''
- container: ''
  name: BlogPostCollection
  type: ''
- container: ''
  name: ScheduleRequest
  type: ''
- container: ''
  name: CloneRequest
  type: ''
- container: ''
  name: PushLiveRequest
  type: ''
- container: ''
  name: ResetDraftRequest
  type: ''
- container: ''
  name: RestorePreviousVersionRequest
  type: ''
- container: ''
  name: VersionHistory
  type: ''
- container: ''
  name: BatchInputItem
  type: ''
- container: ''
  name: BatchInput
  type: ''
- container: ''
  name: BatchResponse
  type: ''
- container: ''
  name: DetachFromLanguageGroupRequest
  type: ''
- container: ''
  name: SetLanguagePrimaryRequest
  type: ''
- container: ''
  name: AttachToLanguageGroupRequest
  type: ''
- container: ''
  name: CreateLanguageVariationRequest
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: PagingNext
  type: ''
- container: ''
  name: PagingPrevious
  type: ''
- container: ''
  name: StandardError
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 22
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-blog-posts-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"BlogPost\": {\n      \"@id\": \"ns:BlogPost\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlTitle\": {\n          \"@id\": \"ns:htmlTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postBody\": {\n          \"@id\": \"ns:postBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postSummary\": {\n          \"@id\": \"ns:postSummary\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blogAuthorId\": {\n          \"@id\": \"ns:blogAuthorId\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"authorName\": {\n          \"@id\": \"ns:authorName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentGroupId\": {\n          \"@id\": \"ns:contentGroupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaign\": {\n          \"@id\": \"ns:campaign\",\n          \"@type\": \"xsd:string\"\n        },\n        \"categoryId\": {\n          \"@id\": \"ns:categoryId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currentState\": {\n          \"@id\": \"ns:currentState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publishDate\": {\n          \"@id\": \"ns:publishDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"ns:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updated\": {\n          \"@id\": \"ns:updated\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"archivedAt\": {\n          \"@id\": \"ns:archivedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currentlyPublished\": {\n          \"@id\": \"ns:currentlyPublished\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"domain\": {\n          \"@id\": \"ns:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"featuredImage\": {\n          \"@id\": \"ns:featuredImage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"featuredImageAltText\": {\n          \"@id\": \"ns:featuredImageAltText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metaDescription\": {\n          \"@id\": \"ns:metaDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"headHtml\": {\n          \"@id\": \"ns:headHtml\",\n          \"@type\": \"xsd:string\"\n        },\n        \"footerHtml\": {\n          \"@id\": \"ns:footerHtml\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n\
  \          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"translatedFromId\": {\n          \"@id\": \"ns:translatedFromId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagIds\": \"ns:tagIds\",\n        \"useFeaturedImage\": {\n          \"@id\": \"ns:useFeaturedImage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"url\": {\n          \"@id\": \"ns:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"abStatus\": {\n          \"@id\": \"ns:abStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"abTestId\": {\n          \"@id\": \"ns:abTestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"folderId\": {\n          \"@id\": \"ns:folderId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BlogPostInput\": {\n      \"@id\": \"ns:BlogPostInput\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlTitle\": {\n          \"@id\": \"ns:htmlTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postBody\": {\n          \"@id\": \"ns:postBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postSummary\": {\n          \"@id\": \"ns:postSummary\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blogAuthorId\": {\n          \"@id\": \"ns:blogAuthorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentGroupId\": {\n          \"@id\": \"ns:contentGroupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"campaign\": {\n          \"@id\": \"ns:campaign\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publishDate\": {\n          \"@id\": \"ns:publishDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"featuredImage\": {\n          \"@id\": \"ns:featuredImage\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"featuredImageAltText\": {\n          \"@id\": \"ns:featuredImageAltText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metaDescription\": {\n          \"@id\": \"ns:metaDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagIds\": \"ns:tagIds\",\n        \"useFeaturedImage\": {\n          \"@id\": \"ns:useFeaturedImage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BlogPostCollection\": {\n      \"@id\": \"ns:BlogPostCollection\",\n      \"@context\": {\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ScheduleRequest\": {\n      \"\
  @id\": \"ns:ScheduleRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publishDate\": {\n          \"@id\": \"ns:publishDate\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CloneRequest\": {\n      \"@id\": \"ns:CloneRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PushLiveRequest\": {\n      \"@id\": \"ns:PushLiveRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ResetDraftRequest\": {\n      \"@id\": \"ns:ResetDraftRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RestorePreviousVersionRequest\": {\n      \"@id\": \"ns:RestorePreviousVersionRequest\",\n\
  \      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"revisionId\": {\n          \"@id\": \"ns:revisionId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"VersionHistory\": {\n      \"@id\": \"ns:VersionHistory\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"ns:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"user\": \"ns:user\",\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchInputItem\": {\n      \"@id\": \"ns:BatchInputItem\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchInput\": {\n      \"@id\": \"ns:BatchInput\",\n      \"@context\": {\n    \
  \    \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchResponse\": {\n      \"@id\": \"ns:BatchResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"links\": \"ns:links\"\n      }\n    },\n    \"DetachFromLanguageGroupRequest\": {\n      \"@id\": \"ns:DetachFromLanguageGroupRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SetLanguagePrimaryRequest\": {\n      \"@id\": \"ns:SetLanguagePrimaryRequest\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AttachToLanguageGroupRequest\": {\n      \"@id\": \"ns:AttachToLanguageGroupRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryId\": {\n          \"@id\": \"ns:primaryId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryLanguage\": {\n          \"@id\": \"ns:primaryLanguage\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CreateLanguageVariationRequest\": {\n      \"@id\": \"ns:CreateLanguageVariationRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prev\": {\n          \"@id\": \"ns:prev\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingPrevious\": {\n      \"@id\": \"ns:PagingPrevious\",\n      \"@context\": {\n        \"before\": {\n          \"@id\": \"ns:before\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"StandardError\"\
  : {\n      \"@id\": \"ns:StandardError\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\":\
  \ \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-blog-posts-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
