---
class_count: 3
classes:
- EmailAttachment
- EmailDLPIncident
- EmailRecipient
context_file: json-ld/palo-alto-email-dlp-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-email-dlp-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Email Dlp Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Email Dlp Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: actionTaken
  type: string
- container: ''
  name: attachmentCount
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: contentType
  type: string
- container: set
  name: dataPatterns
  type: reference
- container: ''
  name: deliveryStatus
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: hasAttachments
  type: boolean
- container: ''
  name: hasMatches
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: matchCount
  type: integer
- container: ''
  name: name
  type: string
- container: set
  name: patternsMatched
  type: string
- container: ''
  name: reviewedAt
  type: dateTime
- container: ''
  name: reviewedBy
  type: string
- container: ''
  name: sender
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: type
  type: string
property_count: 25
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-email-dlp-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmailAttachment\": \"pan:EmailAttachment\",\n    \"EmailDLPIncident\": \"pan:EmailDLPIncident\",\n    \"EmailRecipient\": \"pan:EmailRecipient\",\n    \"actionTaken\": {\n      \"@id\": \"pan:action_taken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentCount\": {\n      \"@id\": \"pan:attachment_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"pan:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"pan:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataPatterns\": {\n      \"@id\": \"pan:data_patterns\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"deliveryStatus\": {\n      \"@id\": \"pan:delivery_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"pan:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"pan:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasAttachments\": {\n      \"@id\": \"pan:has_attachments\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasMatches\": {\n      \"@id\": \"pan:has_matches\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchCount\": {\n      \"@id\": \"pan:match_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patternsMatched\": {\n      \"@id\": \"pan:patterns_matched\",\n      \"\
  @container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewedAt\": {\n      \"@id\": \"pan:reviewed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reviewedBy\": {\n      \"@id\": \"pan:reviewed_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sender\": {\n      \"@id\": \"pan:sender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"pan:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-email-dlp-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
