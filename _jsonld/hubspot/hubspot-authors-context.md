---
class_count: 0
classes: []
context_file: json-ld/hubspot-authors-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-authors-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Authors from HubSpot.
layout: jsonld
name: Hubspot Authors Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: BlogAuthor
  type: ''
- container: ''
  name: BlogAuthorInput
  type: ''
- container: ''
  name: BlogAuthorCollection
  type: ''
- container: ''
  name: BatchInputItem
  type: ''
- container: ''
  name: BatchInput
  type: ''
- container: ''
  name: BatchReadInput
  type: ''
- container: ''
  name: BatchCreateInput
  type: ''
- container: ''
  name: BatchArchiveInput
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
  name: StandardError
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 18
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-authors-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"BlogAuthor\": {\n      \"@id\": \"ns:BlogAuthor\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bio\": {\n          \"@id\": \"ns:bio\",\n          \"@type\": \"xsd:string\"\n        },\n        \"website\": {\n          \"@id\": \"ns:website\",\n          \"@type\": \"xsd:string\"\n        },\n        \"twitter\": {\n          \"@id\": \"ns:twitter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"facebook\": {\n          \"\
  @id\": \"ns:facebook\",\n          \"@type\": \"xsd:string\"\n        },\n        \"linkedin\": {\n          \"@id\": \"ns:linkedin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatar\": {\n          \"@id\": \"ns:avatar\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"translatedFromId\": {\n          \"@id\": \"ns:translatedFromId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"ns:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updated\": {\n          \"@id\": \"ns:updated\",\n          \"@type\": \"xsd:string\"\n        },\n        \"deletedAt\": {\n          \"@id\": \"ns:deletedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BlogAuthorInput\": {\n      \"@id\": \"ns:BlogAuthorInput\",\n      \"@context\": {\n        \"name\": {\n          \"\
  @id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bio\": {\n          \"@id\": \"ns:bio\",\n          \"@type\": \"xsd:string\"\n        },\n        \"website\": {\n          \"@id\": \"ns:website\",\n          \"@type\": \"xsd:string\"\n        },\n        \"twitter\": {\n          \"@id\": \"ns:twitter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"facebook\": {\n          \"@id\": \"ns:facebook\",\n          \"@type\": \"xsd:string\"\n        },\n        \"linkedin\": {\n          \"@id\": \"ns:linkedin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatar\": {\n          \"@id\": \"ns:avatar\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BlogAuthorCollection\": {\n      \"@id\": \"ns:BlogAuthorCollection\"\
  ,\n      \"@context\": {\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchInputItem\": {\n      \"@id\": \"ns:BatchInputItem\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": {\n          \"@id\": \"ns:properties\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"BatchInput\": {\n      \"@id\": \"ns:BatchInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchReadInput\": {\n      \"@id\": \"ns:BatchReadInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchCreateInput\": {\n      \"@id\": \"ns:BatchCreateInput\",\n      \"@context\": {\n        \"inputs\": \"\
  ns:inputs\"\n      }\n    },\n    \"BatchArchiveInput\": {\n      \"@id\": \"ns:BatchArchiveInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchResponse\": {\n      \"@id\": \"ns:BatchResponse\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"requestedAt\": {\n          \"@id\": \"ns:requestedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedAt\": {\n          \"@id\": \"ns:startedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"links\": \"ns:links\"\n      }\n    },\n    \"DetachFromLanguageGroupRequest\": {\n      \"@id\": \"ns:DetachFromLanguageGroupRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"\
  xsd:string\"\n        }\n      }\n    },\n    \"SetLanguagePrimaryRequest\": {\n      \"@id\": \"ns:SetLanguagePrimaryRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AttachToLanguageGroupRequest\": {\n      \"@id\": \"ns:AttachToLanguageGroupRequest\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryId\": {\n          \"@id\": \"ns:primaryId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryLanguage\": {\n          \"@id\": \"ns:primaryLanguage\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CreateLanguageVariationRequest\": {\n      \"@id\": \"ns:CreateLanguageVariationRequest\",\n      \"@context\": {\n        \"id\": {\n          \"\
  @id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"StandardError\": {\n      \"@id\": \"ns:StandardError\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\"\
  : {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\",\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\"\
  : \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-authors-context.jsonld
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
