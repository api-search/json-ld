---
class_count: 0
classes: []
context_file: json-ld/hubspot-domains-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-domains-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Domains from HubSpot.
layout: jsonld
name: Hubspot Domains Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Domain
  type: ''
- container: ''
  name: DomainCollectionResponse
  type: ''
- container: ''
  name: ForwardPaging
  type: ''
- container: ''
  name: NextPage
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 6
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-domains-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Domain\": {\n      \"@id\": \"ns:Domain\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domain\": {\n          \"@id\": \"ns:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isResolving\": {\n          \"@id\": \"ns:isResolving\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isManuallyMarkedAsResolving\": {\n          \"@id\": \"ns:isManuallyMarkedAsResolving\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isSslEnabled\": {\n          \"@id\": \"ns:isSslEnabled\",\n   \
  \       \"@type\": \"xsd:boolean\"\n        },\n        \"isSslOnly\": {\n          \"@id\": \"ns:isSslOnly\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPrimaryBlogPost\": {\n          \"@id\": \"ns:isPrimaryBlogPost\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPrimarySitePage\": {\n          \"@id\": \"ns:isPrimarySitePage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPrimaryLandingPage\": {\n          \"@id\": \"ns:isPrimaryLandingPage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPrimaryEmail\": {\n          \"@id\": \"ns:isPrimaryEmail\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPrimaryKnowledge\": {\n          \"@id\": \"ns:isPrimaryKnowledge\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isUsedForBlogPost\": {\n          \"@id\": \"ns:isUsedForBlogPost\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isUsedForSitePage\": {\n          \"@id\": \"\
  ns:isUsedForSitePage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isUsedForLandingPage\": {\n          \"@id\": \"ns:isUsedForLandingPage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isUsedForEmail\": {\n          \"@id\": \"ns:isUsedForEmail\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isUsedForKnowledge\": {\n          \"@id\": \"ns:isUsedForKnowledge\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"expectedCname\": {\n          \"@id\": \"ns:expectedCname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"redirectTo\": {\n          \"@id\": \"ns:redirectTo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"secondaryToDomain\": {\n          \"@id\": \"ns:secondaryToDomain\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"DomainCollectionResponse\": {\n      \"@id\": \"ns:DomainCollectionResponse\",\n      \"@context\": {\n        \"total\": {\n          \"@id\": \"\
  ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ForwardPaging\": {\n      \"@id\": \"ns:ForwardPaging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"NextPage\": {\n      \"@id\": \"ns:NextPage\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-domains-context.jsonld
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
