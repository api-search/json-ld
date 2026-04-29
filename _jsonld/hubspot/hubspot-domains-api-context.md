---
class_count: 4
classes:
- Domain
- DomainCollectionResponse
- ForwardPaging
- NextPage
context_file: json-ld/hubspot-domains-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-domains-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Domains Api from HubSpot.
layout: jsonld
name: Hubspot Domains Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: isResolving
  type: boolean
- container: ''
  name: isManuallyMarkedAsResolving
  type: boolean
- container: ''
  name: isSslEnabled
  type: boolean
- container: ''
  name: isSslOnly
  type: boolean
- container: ''
  name: isPrimaryBlogPost
  type: boolean
- container: ''
  name: isPrimarySitePage
  type: boolean
- container: ''
  name: isPrimaryLandingPage
  type: boolean
- container: ''
  name: isPrimaryEmail
  type: boolean
- container: ''
  name: isPrimaryKnowledge
  type: boolean
- container: ''
  name: isUsedForBlogPost
  type: boolean
- container: ''
  name: isUsedForSitePage
  type: boolean
- container: ''
  name: isUsedForLandingPage
  type: boolean
- container: ''
  name: isUsedForEmail
  type: boolean
- container: ''
  name: isUsedForKnowledge
  type: boolean
- container: ''
  name: expectedCname
  type: string
- container: ''
  name: redirectTo
  type: string
- container: ''
  name: secondaryToDomain
  type: string
- container: ''
  name: total
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
property_count: 27
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-domains-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Domain\": \"hubspot:Domain\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"hubspot:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"isResolving\": {\n      \"@id\": \"hubspot:isResolving\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isManuallyMarkedAsResolving\": {\n      \"@id\": \"hubspot:isManuallyMarkedAsResolving\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSslEnabled\": {\n      \"@id\": \"hubspot:isSslEnabled\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSslOnly\": {\n      \"@id\": \"hubspot:isSslOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimaryBlogPost\": {\n      \"@id\": \"hubspot:isPrimaryBlogPost\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimarySitePage\": {\n      \"@id\": \"hubspot:isPrimarySitePage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimaryLandingPage\": {\n      \"@id\": \"hubspot:isPrimaryLandingPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimaryEmail\": {\n      \"@id\": \"hubspot:isPrimaryEmail\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimaryKnowledge\": {\n      \"@id\": \"hubspot:isPrimaryKnowledge\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsedForBlogPost\": {\n      \"@id\": \"hubspot:isUsedForBlogPost\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsedForSitePage\": {\n      \"@id\": \"hubspot:isUsedForSitePage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsedForLandingPage\"\
  : {\n      \"@id\": \"hubspot:isUsedForLandingPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsedForEmail\": {\n      \"@id\": \"hubspot:isUsedForEmail\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUsedForKnowledge\": {\n      \"@id\": \"hubspot:isUsedForKnowledge\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"expectedCname\": {\n      \"@id\": \"hubspot:expectedCname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectTo\": {\n      \"@id\": \"hubspot:redirectTo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secondaryToDomain\": {\n      \"@id\": \"hubspot:secondaryToDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DomainCollectionResponse\": \"hubspot:DomainCollectionResponse\",\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"ForwardPaging\": \"hubspot:ForwardPaging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"NextPage\": \"hubspot:NextPage\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-domains-api-context.jsonld
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
