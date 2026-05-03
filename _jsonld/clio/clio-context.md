---
class_count: 0
classes: []
context_file: json-ld/clio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clio/refs/heads/main/json-ld/clio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clio from Clio.
layout: jsonld
name: Clio Context
namespaces:
- prefix: clio
  uri: https://app.clio.com/api/v4/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Matter
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Activity
  type: ''
- container: ''
  name: Bill
  type: ''
- container: ''
  name: TrustAccount
  type: ''
- container: ''
  name: CalendarEntry
  type: ''
- container: ''
  name: Task
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: User
  type: ''
property_count: 9
provider_name: Clio
provider_slug: clio
slug: clio-context
source_filename: clio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clio\": \"https://app.clio.com/api/v4/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Matter\": {\n      \"@id\": \"clio:Matter\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"displayNumber\": \"clio:display_number\",\n        \"description\": \"schema:description\",\n        \"status\": \"clio:status\",\n        \"client\": \"clio:client\",\n        \"openDate\": {\n          \"@id\": \"clio:open_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"closeDate\": {\n          \"@id\": \"clio:close_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n\
  \      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"clio:Contact\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"name\": \"schema:name\",\n        \"type\": \"clio:contact_type\",\n        \"primaryEmail\": \"schema:email\",\n        \"primaryPhone\": \"schema:telephone\"\n      }\n    },\n\n    \"Activity\": {\n      \"@id\": \"clio:Activity\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"type\": \"clio:activity_type\",\n        \"date\": {\n          \"@id\": \"clio:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"quantityInSeconds\": \"clio:quantity_in_seconds\",\n        \"rate\": \"clio:rate\",\n        \"total\": \"clio:total\",\n        \"matter\": \"clio:matter\",\n        \"user\": \"clio:user\",\n        \"billable\": \"clio:billable\"\n      }\n    },\n\n    \"Bill\": {\n      \"@id\": \"clio:Bill\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"number\": \"clio:number\",\n        \"issuedAt\": {\n\
  \          \"@id\": \"clio:issued_at\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dueAt\": {\n          \"@id\": \"clio:due_at\",\n          \"@type\": \"xsd:date\"\n        },\n        \"state\": \"clio:state\",\n        \"subject\": \"clio:subject\",\n        \"total\": \"clio:total\"\n      }\n    },\n\n    \"TrustAccount\": {\n      \"@id\": \"clio:TrustAccount\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"name\": \"schema:name\",\n        \"balance\": \"clio:balance\"\n      }\n    },\n\n    \"CalendarEntry\": {\n      \"@id\": \"clio:CalendarEntry\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"summary\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"startAt\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endAt\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": \"schema:location\"\
  \n      }\n    },\n\n    \"Task\": {\n      \"@id\": \"clio:Task\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"dueAt\": {\n          \"@id\": \"clio:due_at\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"clio:status\",\n        \"priority\": \"clio:priority\"\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"clio:Document\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"name\": \"schema:name\",\n        \"filename\": \"clio:filename\",\n        \"contentType\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"clio:User\",\n      \"@context\": {\n        \"id\": \"clio:id\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\"\
  ,\n        \"enabled\": \"clio:enabled\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clio/refs/heads/main/json-ld/clio-context.jsonld
tags:
- Billing
- Calendaring
- Document Management
- Law Firms
- Legal
- Matter Management
- OAuth 2.0
- Practice Management
- Time Tracking
- Trust Accounting
- JSON-LD
- Linked Data
- Semantic Web
---
