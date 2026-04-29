---
class_count: 9
classes:
- SmtpToken
- SmtpTokenWithPassword
- SmtpTokenCollectionResponse
- SmtpTokenCreateRequest
- TransactionalEmailRequest
- EmailMessage
- TransactionalEmailResponse
- Paging
- NextPage
context_file: json-ld/hubspot-marketing-emal-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-marketing-emal-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Marketing Emal Api from HubSpot.
layout: jsonld
name: Hubspot Marketing Emal Api Context
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
  name: campaignName
  type: string
- container: ''
  name: emailCampaignId
  type: string
- container: ''
  name: createContact
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: ''
  name: password
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: emailId
  type: integer
- container: ''
  name: message
  type: reference
- container: ''
  name: contactProperties
  type: reference
- container: ''
  name: customProperties
  type: reference
- container: ''
  name: to
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: sendId
  type: string
- container: set
  name: replyTo
  type: string
- container: set
  name: cc
  type: string
- container: set
  name: bcc
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusId
  type: string
- container: ''
  name: sendResult
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
  name: next
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
property_count: 28
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-marketing-emal-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SmtpToken\": \"hubspot:SmtpToken\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignName\": {\n      \"@id\": \"hubspot:campaignName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailCampaignId\": {\n      \"@id\": \"hubspot:emailCampaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createContact\": {\n      \"@id\": \"hubspot:createContact\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"hubspot:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SmtpTokenWithPassword\": \"hubspot:SmtpTokenWithPassword\",\n\
  \    \"password\": {\n      \"@id\": \"hubspot:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SmtpTokenCollectionResponse\": \"hubspot:SmtpTokenCollectionResponse\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"SmtpTokenCreateRequest\": \"hubspot:SmtpTokenCreateRequest\",\n    \"TransactionalEmailRequest\": \"hubspot:TransactionalEmailRequest\",\n    \"emailId\": {\n      \"@id\": \"hubspot:emailId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"@id\"\n    },\n    \"contactProperties\": {\n      \"@id\": \"hubspot:contactProperties\",\n      \"@type\": \"@id\"\n    },\n    \"customProperties\": {\n      \"@id\": \"hubspot:customProperties\",\n      \"@type\": \"@id\"\n    },\n    \"EmailMessage\": \"hubspot:EmailMessage\",\n   \
  \ \"to\": {\n      \"@id\": \"hubspot:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"hubspot:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendId\": {\n      \"@id\": \"hubspot:sendId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replyTo\": {\n      \"@id\": \"hubspot:replyTo\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cc\": {\n      \"@id\": \"hubspot:cc\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bcc\": {\n      \"@id\": \"hubspot:bcc\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionalEmailResponse\": \"hubspot:TransactionalEmailResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusId\": {\n      \"@id\": \"hubspot:statusId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sendResult\": {\n      \"@id\": \"hubspot:sendResult\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"NextPage\": \"hubspot:NextPage\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-marketing-emal-api-context.jsonld
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
