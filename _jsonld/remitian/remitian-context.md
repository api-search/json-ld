---
api_specs:
- filename: remitian-tax-payment-openapi.yml
  format: yaml
  label: Remitian Tax Payment API
  slug: tax-payment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/remitian/refs/heads/main/openapi/remitian-tax-payment-openapi.yml
class_count: 0
classes: []
context_file: json-ld/remitian-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/remitian/refs/heads/main/json-ld/remitian-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Remitian from Remitian.
layout: jsonld
name: Remitian Context
namespaces:
- prefix: remitian
  uri: https://remitian.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: TaxPayment
  type: ''
- container: ''
  name: TaxJurisdiction
  type: ''
- container: ''
  name: ClientAccount
  type: ''
- container: ''
  name: BankConnection
  type: ''
- container: ''
  name: AuditLogEntry
  type: ''
- container: ''
  name: WebhookSubscription
  type: ''
property_count: 6
provider_name: Remitian
provider_slug: remitian
slug: remitian-context
source_filename: remitian-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"remitian\": \"https://remitian.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"TaxPayment\": {\n      \"@id\": \"remitian:TaxPayment\",\n      \"@context\": {\n        \"paymentId\": \"remitian:paymentId\",\n        \"status\": \"remitian:paymentStatus\",\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxType\": \"remitian:taxType\",\n        \"taxPeriod\": \"remitian:taxPeriod\",\n        \"jurisdictionId\": \"remitian:jurisdictionId\",\n        \"accountId\": \"remitian:accountId\",\n        \"taxIdentifier\": \"remitian:taxIdentifier\",\n        \"confirmationNumber\": \"remitian:confirmationNumber\",\n        \"createdAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TaxJurisdiction\": {\n      \"@id\": \"remitian:TaxJurisdiction\",\n      \"@context\": {\n        \"jurisdictionId\": \"remitian:jurisdictionId\",\n        \"name\": \"schema:name\",\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jurisdictionType\": \"remitian:jurisdictionType\",\n        \"taxTypes\": {\n          \"@id\": \"remitian:taxTypes\",\n          \"@container\": \"@set\"\n        },\n        \"requiredFields\": {\n          \"@id\": \"remitian:requiredFields\",\n          \"@container\": \"@set\"\n        },\n        \"paymentMethods\": {\n          \"@id\": \"schema:paymentMethod\",\n          \"@container\": \"@set\"\n        },\n        \"active\": {\n\
  \          \"@id\": \"remitian:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ClientAccount\": {\n      \"@id\": \"remitian:ClientAccount\",\n      \"@context\": {\n        \"accountId\": \"remitian:accountId\",\n        \"name\": \"schema:name\",\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxIdentifier\": \"remitian:taxIdentifier\",\n        \"bankConnections\": {\n          \"@id\": \"remitian:bankConnections\",\n          \"@container\": \"@set\"\n        },\n        \"status\": \"remitian:accountStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BankConnection\": {\n      \"@id\": \"remitian:BankConnection\",\n      \"@context\": {\n        \"connectionId\": \"remitian:connectionId\",\n        \"institutionName\": \"schema:name\",\n        \"accountLast4\": \"remitian:accountLast4\"\
  ,\n        \"status\": \"remitian:connectionStatus\",\n        \"verifiedAt\": {\n          \"@id\": \"remitian:verifiedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AuditLogEntry\": {\n      \"@id\": \"remitian:AuditLogEntry\",\n      \"@context\": {\n        \"entryId\": \"remitian:entryId\",\n        \"paymentId\": \"remitian:paymentId\",\n        \"accountId\": \"remitian:accountId\",\n        \"eventType\": \"remitian:eventType\",\n        \"description\": \"schema:description\",\n        \"actor\": \"remitian:actor\",\n        \"ipAddress\": \"remitian:ipAddress\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookSubscription\": {\n      \"@id\": \"remitian:WebhookSubscription\",\n      \"@context\": {\n        \"webhookId\": \"remitian:webhookId\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n\
  \        \"events\": {\n          \"@id\": \"remitian:subscribedEvents\",\n          \"@container\": \"@set\"\n        },\n        \"active\": {\n          \"@id\": \"remitian:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/remitian/refs/heads/main/json-ld/remitian-context.jsonld
tags:
- Tax
- Payments
- Fintech
- Accounting
- Webhooks
- Embedded Payments
- JSON-LD
- Linked Data
- Semantic Web
---
