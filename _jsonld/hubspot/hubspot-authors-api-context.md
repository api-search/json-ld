---
class_count: 15
classes:
- BlogAuthor
- BlogAuthorInput
- BlogAuthorCollection
- BatchInputItem
- BatchInput
- BatchReadInput
- BatchCreateInput
- BatchArchiveInput
- BatchResponse
- DetachFromLanguageGroupRequest
- SetLanguagePrimaryRequest
- AttachToLanguageGroupRequest
- CreateLanguageVariationRequest
- Paging
- PagingNext
context_file: json-ld/hubspot-authors-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-authors-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Authors Api from HubSpot.
layout: jsonld
name: Hubspot Authors Api Context
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
  name: name
  type: ''
- container: ''
  name: slug
  type: string
- container: ''
  name: email
  type: ''
- container: ''
  name: bio
  type: string
- container: ''
  name: website
  type: reference
- container: ''
  name: twitter
  type: string
- container: ''
  name: facebook
  type: string
- container: ''
  name: linkedin
  type: string
- container: ''
  name: avatar
  type: reference
- container: ''
  name: language
  type: string
- container: ''
  name: translatedFromId
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: deletedAt
  type: dateTime
- container: ''
  name: total
  type: integer
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: properties
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: requestedAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: links
  type: reference
- container: ''
  name: primaryId
  type: string
- container: ''
  name: primaryLanguage
  type: string
- container: ''
  name: next
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
property_count: 30
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-authors-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BlogAuthor\": \"hubspot:BlogAuthor\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"slug\": {\n      \"@id\": \"hubspot:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"bio\": {\n      \"@id\": \"hubspot:bio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"website\": {\n      \"@id\": \"hubspot:website\",\n      \"@type\": \"@id\"\n    },\n    \"twitter\": {\n      \"@id\": \"hubspot:twitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facebook\": {\n      \"@id\": \"hubspot:facebook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linkedin\"\
  : {\n      \"@id\": \"hubspot:linkedin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatar\": {\n      \"@id\": \"hubspot:avatar\",\n      \"@type\": \"@id\"\n    },\n    \"language\": {\n      \"@id\": \"hubspot:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"translatedFromId\": {\n      \"@id\": \"hubspot:translatedFromId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"hubspot:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"hubspot:updated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deletedAt\": {\n      \"@id\": \"hubspot:deletedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"BlogAuthorInput\": \"hubspot:BlogAuthorInput\",\n    \"BlogAuthorCollection\": \"hubspot:BlogAuthorCollection\",\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n \
  \     \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"BatchInputItem\": \"hubspot:BatchInputItem\",\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"BatchInput\": \"hubspot:BatchInput\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchReadInput\": \"hubspot:BatchReadInput\",\n    \"BatchCreateInput\": \"hubspot:BatchCreateInput\",\n    \"BatchArchiveInput\": \"hubspot:BatchArchiveInput\",\n    \"BatchResponse\": \"hubspot:BatchResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"\
  @id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"links\": {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"DetachFromLanguageGroupRequest\": \"hubspot:DetachFromLanguageGroupRequest\",\n    \"SetLanguagePrimaryRequest\": \"hubspot:SetLanguagePrimaryRequest\",\n    \"AttachToLanguageGroupRequest\": \"hubspot:AttachToLanguageGroupRequest\",\n    \"primaryId\": {\n      \"@id\": \"hubspot:primaryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryLanguage\": {\n      \"@id\": \"hubspot:primaryLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateLanguageVariationRequest\": \"hubspot:CreateLanguageVariationRequest\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"PagingNext\": \"hubspot:PagingNext\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"\
  hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-authors-api-context.jsonld
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
